<h1 align="center">Alexandra Hotel Website</h1>

<a href="https://backstagecrewis.github.io/" target="_blank">Live site link</a>

A basic website for The Alexandra Hotel using HTML, CSS and a Bootstrap framework
It is designed with mobile users in mind as many of the site visitors will be 

![Alexandra Hotel](/assets/images/alexandra-outside.jpg "Alexandra Hotel Exterior")

#### Table of Contents

- [User Experience UX](#user-experience-ux)
- [Design Strategy](#design-strategy)
- [Features](#features)
- [Technologies Used](#Technologies-Used)
- [Testing](#Site-Testing)


## User Experience (UX)

* ### User Stories
  - #### First Time Visitor Goals
  
    a. As a first time visitor, I want to know that I am on the correct website. (There is more than one Alexandra Hotel).

    b. As a first time visitor, I want to be able to use the site to find the information I am looking for.

    c. As a first time visitor, I want the site to be intuitive. I want to be able to understand the navigation without instructions.
    
    d. As a first time visitor, I want to find directions to the pub.

  - #### Returning Visitor Goals
  
    a. As a returning visitor, I want to know what beers are available before my visit to the hotel.
    
    b. As a returning visitor, I want to be able to find the contact form to send a message to the pub,
    
    c. As a returning visitor, I want to find information about boking a room for the night.

  - #### Frequent User Goals
  
    a. As a frequent user, I want to see what beers are available.
    
    b. As a returning visitor, I want more information about continental beers.
    
    c. As a frequent user, I want to find links to the pub's social media accounts.

* Design Considerations
  - Colour Scheme
    The main colours on the pub sign are blue and gold. The colour scheme should reflect this
    
  - Typography
    To ensure clarity of text on the website, a sans serif font is preferred.
    The Poppins font has a variety of sizes available and will be used with Sans Serif as a backup in case the desired font fails to load.
    The header should reflect the font and text used on the pub sign. This is a gold coloured serif font on a blue background.
    
  - Imagery
    A large hero image of the pub at the top of the landing page will serve to illustrate the pub and to reassure that the visitor is looking at the correct site
    A heading which includes a representation of the pub sign will further reinforce the brand image od the pub

* Wireframes
  - Home Page Wireframe - <a href="/assets/wireframes/index.png" target="_blank">View</a>
  - Beer Page Wireframe - <a href="/assets/wireframes/beers.png" target="_blank">View</a>
  - Rooms Page Wireframe - <a href="/assets/wireframes/rooms.png" target="_blank">View</a>
  - Contact Page Wireframe - <a href="/assets/wireframes/contact.png" target="_blank">View</a>


## Design Strategy

### The strategy plane:
**What are you aiming to achieve in the first place and for whom?**

The website is for The Alexandra Hotel as a simple online advertisement of what is available when a customer visits the pub.

The users will be a mixture of local regular visitors and tourists / travellers visiting the area.

### The scope plane:
**Which features, based on information from the strategy plane, do you want to include in your design?**

#### Must Have
A welcome message and some information about the pub.

The pub serves a range of regular beers and would like to give information about each of them. This will be the name of the brewery, the beer name, the abv (strength) and some tasting notes. A picture of the pump clip will help the visitor locate the beer on the bar.

The pub serves a large range of continental bottled beers and would like to have a list of these available. This can be provided using a link to download a pdf from the beers page.

The pub has three guest rooms where visitors can stay the night and would like to show information about them.

#### Could Have
A simple contact form would be useful for people to enquire about room bookings.

A map and directions to the pub is desireable.

#### Future plans
In the future it would be desirable for the landlord to be able to update the guest beers on the site without having to resort to coding.

#### Usability
Most users are assumed to be accessing the site on a mobile device so the site should adopt a mobile first design.

Users should be able to navigate the site without difficulty so navigation should be intuitive.

For the initial build, this site will incorporate:
* Welcome message and information about the pub
* A list of regularly available beers with details
* A downloadable list of continental beers
* Some information about the available rooms and facilities
* Information and directions to the pub with a local map showing the location
* A contact form to email enquiries

Future Development:
* Add a method to add and remove guest beers to the beer list (methodology to be determined)
* Link beers to Untappd.com so users can 'check in' the beers they are drinking

### The structure plane:
**How is the information structured and how is it logically grouped?**

The information should be grouped by;

* Welcome and information
* Beers
* Rooms and facilities
* Location information and contact form

The landing page should contain a welcome message and basic information about the pub. There should also be a navigation area to other areas of the site.

The beer list should be on a separate page with a link to download the continental beer list.

Another page should show the rooms and facilities with a link to the contact page for enquiries.

Information and directions with a map should be on a fourth page. This page will contain the contact form.

All pages should have navigation links to the other pages.


### The skeleton plane:
**How will our information be represented, and how will the user navigate to the information and the features?**

index.html
The landing page will contain a welcome message and basic information about the pub. There should also be a navigation area to other areas of the site.

beers.html
The list of beers with a link to the pdf containing the list of continental beers

rooms.html
Information about the rooms and facilities with at least one image per room

contact.html
A contact form
A local area map and directions to the pub from the railway station and the bus station.
The directions will have images to help the user to begin their navigation

A navigation area must be included on each page to allow the user to move between pages
The links will all open in the same tab except for the link to the pdf which will open in a new tab.


### The surface plane:
**What will the finished product look like? What colors, typography, and design elements will we use?**
Wireframes for each of the pages are below:

<a href="/assets/wireframes/index.png" target="_blank">index.html Wireframe</a>

<a href="/assets/wireframes/beers.png" target="_blank">beers.html Wireframe</a>

<a href="/assets/wireframes/rooms.png" target="_blank">rooms.html Wireframe</a>

<a href="/assets/wireframes/contact.png" target="_blank">contact.html Wireframe</a>

The colour scheme of the pub sign is blue and gold while the building is painted white.
This can be reflected in the website by using a white background with blue and gold as a colour scheme for navigation menu items and buttons

## Features

### Responsive
The site must be designed to work on on all devices from mobile to desktop.

### Intuitive
Navigation and use of the website must be intuitive allowing the user to be able to use the website without instructions


## Technologies Used

### Languages Used
[HTML5](https://en.wikipedia.org/wiki/HTML5)

[CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used

[Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
Bootstrap was used to assist with the responsiveness and styling of the website.

[Google Fonts:](https://fonts.google.com/)
Google fonts were used to import the 'Poppins' font into the style.css file which is used on all pages throughout the project.
The pub sign in the header uses 'Hahmlet' font because it is a close match to the font used on the actual pub sign.

[Font Awesome:](https://fontawesome.com/)
Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

jQuery:
jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.

[Git](https://git-scm.com/)
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

[GitHub:](https://github.com/)
GitHub is used to store the projects code after being pushed from Git.

[Adobe Fireworks CS6:](https://www.adobe.com)
Fireworks CS6 was used to create the logo, resizing images and editing photos for the website.

[Balsamiq:](https://balsamiq.com/)
Balsamiq was used to create the wireframes during the design process.

## Image Credits

The image of the hotel exterior was provided by the hotel who retain the rights to their image.

The room images are placeholders which were sourced from [Pexels.com](https://www.pexels.com/license/) and are licenced to use for this purpose.

The map and streetview images on the contact page are taken from [Google Maps](https://www.google.com/intl/en-GB_ALL/permissions/geoguidelines/) which is free to use with direct links to the Google Maps content.
[Licencing Infomation](https://www.google.com/intl/en-GB_ALL/permissions/geoguidelines/#:~:text=Using%20Street%20View%20imagery)

The pump clip images and tasting notes for the beers were sourced from [The Real Ale Database](https://realaledb.com)
The information on this site is free to use under [Fair Dealing for Private Study](https://www.gov.uk/guidance/exceptions-to-copyright#non-commercial-research-and-private-study:~:text=as%20amended.-,Non%2Dcommercial%20research%20and%20private%20study,-You%20are%20allowed) as the site do not profit from and share their data freely.



## Site Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

W3C Markup Validator - [Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbackstagecrewis.github.io%2F)

W3C CSS Validator - [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbackstagecrewis.github.io%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)


Testing User Stories from User Experience (UX) Section

* ### User Stories
  - #### First Time Visitor Goals
  
    a. As a first time visitor, I want to know that I am on the correct website. (There is more than one Alexandra Hotel).

    A large hero image with a replica of the pub sign are at the top of the landing page to show that the user is on the correct site

    b. As a first time visitor, I want to be able to use the site to find the information I am looking for.

    The basic information about the pub is displayed on the landing page. Further information is on the relevant pages.

    c. As a first time visitor, I want the site to be intuitive. I want to be able to understand the navigation without instructions.

    There is a large navigation menu on the landing page and all subsequent pages that is always in the same place with the links in the same order. This makes it easy to learn and to find the desired link.
    
    d. As a first time visitor, I want to find directions to the pub.

    The contact page includes a map and comprehensive direction including links to Google Streetview.

  - #### Returning Visitor Goals
  
    a. As a returning visitor, I want to know what beers are available before my visit to the hotel.

    The beers page includes all of the desired information about the regular beers and a link to download the pdf of the continental beer selection.
    
    b. As a returning visitor, I want to be able to find the contact form to send a message to the pub,

    The contact form is on the contact page and also linked from the rooms page to guide the user.
    
    c. As a returning visitor, I want to find information about booking a room for the night.

    The rooms page includes information about booking a room with a direct link to the contact form for any enquiries

  - #### Frequent User Goals
  
    a. As a frequent user, I want to see what beers are available.

    The beers page includes all of the desired information about the regular beers and a link to download the pdf of the continental beer selection
    
    b. As a returning visitor, I want more information about continental beers.

    The beers page includes all of the desired information about the regular beers and a link to download the pdf of the continental beer selection
    
    c. As a frequent user, I want to find links to the pub's social media accounts.

    The footer of each page contains links to each of the pub's social media accounts


Further Testing

The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and the mobile phone browser.

The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, Sony Xperia XZ2.

The site was also tested for responsive behaviour on [ui.dev amiresponsive](https://ui.dev/amiresponsive?url=https://backstagecrewis.github.io/) and[responsivedesignchecker](http://responsivedesignchecker.com/checker.php?url=https%3A%2F%2Fbackstagecrewis.github.io%2F&width=1400&height=700) both of which confirmed that the site is behaving as expected on a the full range of devices.

A large amount of testing was done to ensure that all pages were linking correctly.

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

Known Bugs

Below 269 pixels, the pub sign text starts to move beyond the frame of the sign. In futute versions, theere will be a forther section of media queries to further reduce the font size.

