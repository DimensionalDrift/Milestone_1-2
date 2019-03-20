# Milestone 1 - Spot Magazine Website Redesign

This is my redesign of the website of a client who owns a travel magazine in Switzerland. It features the design of five sample pages as requested by the client, a live demo of which can be found [here](https://dimensionaldrift.github.io/Milestone_1/index.html).

## UX

In our initial design brief the client outlined the requirements of the website and the business. The website required:

 - a front page to feature links to the stories from the magazine
 - a sample design of a story from the magazine
 - a gallery with links to digital copies of previous issues
 - a page with details and a form to enter a photo competition
 - a contact/about page for the magazine staff

My initial design was based on multiple sources including her website, the design featured in the magazine and some sample websites for inspiration (all of which can be found [below](#design-references-supplied-by-the-client)). My initial mockups can be found in the assets folder above. 


Here are user stories that came up during our design meetings or during development:
 - As the customer I would like some of the design elements featured in the magazine to feature on the website.
 - As the customer I would like my photographs to be a main feature on the site.
 - As the user I would like to enter the photo competition using an online form.
 - As the customer I would like a gallery of the previous issues of the magazine.
 - As the customer I would like an easy way for potential customers or clients to contact my business. 
 - As a user I would like to know that a link is clickable.

## Technologies Used

1. HTML
2. CSS
3. Bootstrap (4.2.1)
4. Font Awesome (4.7.0)
5. Google Font (https://fonts.googleapis.com/css?family=Pacifico)

## Features

I felt the current design of the website lacked some of the design elements from the magazine so I tried to include some where I could. For example I featured important images inside circular frames and used a handwritten font similar to one in the magazine. I also featured circular 'Spot' icons for interactive elements like social media links, further emulating the circular theme of the logo. 

The color pallet for the website is quite simple by request of the client. It features 'Spot' red from the logo, white and an off grey color. Since that is the case I tried to use colored accents sparingly, Only using 'Spot' red for icons, buttons and interactive element highlights and the grey for secondary content like the footer and the info card on the story page.

Photography is an important part of the magazine so I also tried to feature images as large as possible on the site which is the inspiration of the full height 'Hero' image on the home page.

While building the website it became clear that it is important to give visual feedback to the user. For example it is important to show that some elements are clickable or that there is more content to scroll down to on the front page. From this thought, a few subtle visual cues have been included on the site. Examples include a light hover effect over story summaries or the magazines in the gallery, or the bouncing downward arrow that either invites the user to scroll or can be clicked to automatically scroll the user to the featured story.

It is also important to the client, as it is for almost all modern businesses, that the website was responsive and mobile friendly. It is particularly important to design for tablet sized displays as she uses one when speaking to potential advertisers to showcase her brand. With that in mind the website is designed mobile first with different layouts for incrementally larger screens. This can be seen when looking at the prizes section of the contest page, each screen size utilizes a different layout. 


## Future Features

There are some features that the client requested that are unfortunately outside the scope of this project. Such features include:

 - The search 'Spot' at the top of the screen is non functional at the moment. In the intended design, when the user clicks the search icon it will reveal the search box with a sliding animation. In order to animate this it will require custom JavaScript and other libraries that are outside the scope of this project.

 - It is also intended that on the home page that the navigation bar at the top will be transparent, allowing the photo take up the whole screen but to implement that will require more custom JavaScript.

 - No forms or user input have been hooked up to any backend system, this will definitely need to be changed in the future.

 - On the front page the client would like the user to be able to read and explore the stories from the magazine. Currently there are only 6 stories displayed but in the future the 'More' button below them will continually generate more story cards. This has not been implemented as it will require the use of custom JavaScript.

 - The client would like an interactive map of Switzerland, where users can explore certain areas of the country to read stories and features from that region. This will require the use of API's which I know will be covered in the next section of the course.

 - The developer that designed and built her current website also created a custom tool in the backend to make publishing to the website as easy as possible. In the future, this current design will need to include features to make it compatible with that tool. 

 - The client would also like to have an interactive Instagram feed featured on the front page. Again this will require a JavaScript library such as Instafeed.js or juicer.io and will also require custom JavaScript to design.

 - When the bouncing icon is clicked on the front page it uses 'scroll-behavior: smooth' to scroll to the featured story. It is known that this isn't fully supported in all browsers yet and could be better implemented with something like the 'Animate on scroll' library to achieve the effect cross browser.

 - The client would like to use icons to indicate to readers what the story might feature such as nature and sport icons. In the future it will be possible to upgrade from Font Awesome to the latest version as it features many more icons than the version used (4.7.0).


## Testing

The website was tested extensively during development in Chrome Beta on Kubuntu Linux. The page was tested for layout arrangements in different form factors and that interactive elements were responsive. The site was also tested on Chrome Beta for Android to make sure the layout made sense when actually viewed on a mobile screen rather than the responsive screen of a desktop browser. 

Checking the browser market share for Switzerland [here](http://gs.statcounter.com/browser-market-share/all/switzerland) it is a near tie between Safari and Chrome and between mobile and desktop so it was most important to check that the website worked on those browsers in those form factors. 

Once the site was nearing completion it was tested on multiple devices including multiple Android phones, a Chromebook, Chrome and Firefox in Windows 10, Firefox in Linux and both mobile and desktop Safari. During that testing phase it was found there was a major bug with the websites scrolling when viewed using iOS Safari. It was caused by another bug fix used early on in development which has since been removed as it does not appear to be an issue any more.

## Deployment

Since this is only a static design preview the website only needs to be deployed using GitHub Pages. This was done by enabling the option in the GitHub repository and ensuring that the repository was structured correctly. GitHub Pages has been used to host all versions of the website during development as it was the easiest way to lease with the client and showcase multiple designs. There is an example of a period where multiple designs were being considered for the layout of the front page that can be found [here](https://dimensionaldrift.github.io/Milestone_1/old/index_designtest.html).

## Credits

### Content
All text content was either written by me, supplied by Sublime Texts built in lorem ipsum or generated using https://www.blindtextgenerator.com/lorem-ipsum.

### Media
 - All images were supplied by © Spot Media GmbH. 
 - Dummy images were found at http://dummy-image-generator.com/

### Resources 
The bulk of learning and referencing for this project used either Code Institute lessons, the Bootstrap documentation or W3schools examples and lessons. 
Beyond that any issues that could not be solved using the above resources were mostly found on Stack Overflow. A list of links to any code snippets that were used in the projects can either be found commented throughout the code or in a list [below](#code-snippets-used).

### Acknowledgments
I would like to thank Carina Scheuringer and Spot Magazine for being the inspiration for the project. I would also like to thank her for the use of her photos and materials for this project.
I would like to thank my friends and family for being bug testers and giving their valuable feedback.

#### Code snippets used 
- https://stackoverflow.com/questions/4617872/white-space-showing-up-on-right-side-of-page-when-background-image-should-extend
- https://stackoverflow.com/questions/8118741/css-font-helvetica-neue
- https://stackoverflow.com/questions/17631417/css-pure-css-scroll-animation
- https://www.igorkromin.net/index.php/2016/05/20/mobile-safari-scrolling-problem-with-an-input-field-inside-a-fixed-div/
- https://stackoverflow.com/questions/16670931/hide-scroll-bar-but-while-still-being-able-to-scroll
- https://stackoverflow.com/questions/22559756/changing-hover-to-touch-click-for-mobile-devices
- https://codepen.io/jmelgoza/pen/jEaGYg
- https://www.w3schools.com/howto/howto_css_image_overlay.asp
- https://bootstrapformbuilder.com/
- https://www.materialui.co/socialcolors
- https://codepen.io/thomasrye/pen/VaRoYv

#### Design references supplied by the client
 - https://www.spotmagazine.ch/
 - https://en.calameo.com/read/002969344fea1dbf87173?
 - https://www.rhb.ch/en/home
 - https://www.madeinbern.com/en/home-en#top
 - https://www.zuerich.com/en

<!-- 
Ideas
    Use JSON to fill in details of stories on the page

    Implement Jasmine testing 
    Use Jasmine to check that stories are not too long for the page
 
 -->

 <!-- X Greater to do list:
        - Check that the hover effect for the story and magazine links funtionally works ok on mobile
        - Edit the style of the carousel buttons, maybe a 1/3 red spot on either side?
 -->
 

