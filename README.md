<h1 align="center">Alexandra Hotel Website</h1>
[Link to the live website when built]

A basic website for The Alexandra Hotel using HTML, CSS and a Bootstrap framework
It is designed with mobile users in mind as many of the site visitors will be 

![Alexandra Hotel](/assets/images/alexandra-outside.jpg "Alexandra Hotel Exterior")

#### Table of Contents

- [User Experience UX](#user-experience-ux)
- [Design Strategy](#design-strategy)
- [Features](#features)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)


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

  - Rule of Thirds
    Using the Rule of Thirds techniques will give the page better clarity and balance

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

[Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
Photoshop was used to create the logo, resizing images and editing photos for the website.

[Balsamiq:](https://balsamiq.com/)
Balsamiq was used to create the wireframes during the design process.

## Image Credits

All the images for the website (with the exception of the room images) were provided by the hotel who retain the rights to their images.

The room images are placeholders which were sourced from [Pexels.com](https://www.pexels.com/license/) and are licenced to use for this purpose.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

W3C Markup Validator - Results

W3C CSS Validator - Results

Testing User Stories from User Experience (UX) Section

First Time Visitor Goals

As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.

Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. 

Underneath there is a Hero Image with Text and a "Learn More" Call to action button.

The main points are made immediately with the hero image

The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

The site has been designed to be fluid and never to entrap the user. 
At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.

At the bottom of the first 3 pages there is a redirection call to action to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.

On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.

Once the new visitor has read the About Us and What We Do text, they will notice the Why We are Loved So Much section.

The user can also scroll to the bottom of any page on the site to locate social media links in the footer.

At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

Returning Visitor Goals

As a Returning Visitor, I want to find the new programming challenges or hackathons.

These are clearly shown in the banner message.

They will be directed to a page with another hero image and call to action.

As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.

The navigation bar clearly highlights the "Contact Us" Page.

Here they can fill out the form on the page or are told that alternatively they can message the organisation on social media.

The footer contains links to the organisations Facebook, Twitter and Instagram page as well as the organization's email.

Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

The email button is set up to automatically open up your email app and autofill there email address in the "To" section.

As a Returning Visitor, I want to find the Facebook Group link so that I can join and interact with others in the community.

The Facebook Page can be found at the footer of every page and will open a new tab for the user and more information can be found on the Facebook page.

Alternatively, the user can scroll to the bottom of the Home page to find the Facebook Group redirect card and can easily join by clicking the "Join Now!" button which like any external link, will open in a new tab to ensure they can get back to the website easily.

If the user is on the "Our Favourites" page they will also be greeted with a call to action button to invite the user to the Facebook group.

The user is incentivized as they are told there is a weekly favourite product posted in the group.

Frequent User Goals

As a Frequent User, I want to check to see if there are any newly added challenges or hackathons.

The user would already be comfortable with the website layout and can easily click the banner message.

As a Frequent User, I want to check to see if there are any new blog posts.

The user would already be comfortable with the website layout and can easily click the blog link

As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

At the bottom of every page their is a footer which content is consistent throughout all pages.

To the right hand side of the footer the user can see "Subscribe to our Newsletter" and are prompted to Enter their email address.

There is a "Submit" button to the right hand side of the input field which is located close to the field and can easily be distinguished.

Further Testing

The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.

The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.

A large amount of testing was done to ensure that all pages were linking correctly.

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

Known Bugs

On some mobile devices the Hero Image pushes the size of screen out more than any of the other content on the page.

A white gap can be seen to the right of the footer and navigation bar as a result.

On Microsoft Edge and Internet Explorer Browsers, all links in Navbar are pushed upwards when hovering over them.