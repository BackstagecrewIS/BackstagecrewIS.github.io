# Alexandra Hotel
A basic website for The Alexandra Hotel using HTML, CSS and a Bootstrap framework

![Alexandra Hotel](/assets/img/alexandra-outside.jpg "Alexandra Hotel Exterior")

#### Table of Contents

- [Design Strategy](#design-strategy)
- [](#)
- [](#)
- [](#)


## Design Strategy

### The strategy plane:
**What are you aiming to achieve in the first place and for whom?**

The website is for The Alexandra Hotel as a simple online advertisement of what is available when a customer visits the pub.

The users will be a mixture of local regular visitors and tourists / travellers visiting the area.

### The scope plane:
**Which features, based on information from the strategy plane, do you want to include in your design?**

#### Must Have
A welcome message and some information about the pub.

The pub serves a range of regular beers and would like to give information about each of them.

The pub serves a large range of continental bottled beers and would like to have a list of these available.

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
* A list of regularly available beers
* A downloadable list of continental beers
* Some information about the available rooms and facilities
* Information and directions to the pub with a local map showing the location
* Contact form to email enquiries

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
Wireframes for each of the pages is below:

<a href="/assets/wireframes/index-mobile.png" target="_blank">index.html Wireframe</a>

<a href="/assets/wireframes/beers-mobile.png" target="_blank">beers.html Wireframe</a>

<a href="/assets/wireframes/rooms-mobile.png" target="_blank">rooms.html Wireframe</a>

<a href="/assets/wireframes/contact-mobile.png" target="_blank">contact.html Wireframe</a>


A good README.md file has a link to the live deployed project.
It helps the reader understand what the project does, what technologies have been used, what
features you'd like to add. And, it also gives credit for any code that's been
taken from other places, such as libraries that you might have imported,
or code that you found on Stack Overflow. Even code that fellow students have
helped you with, it's good to credit it here.

It should also contain screenshots of your finished project and details about
how you tested and deployed the project, and also how someone could clone and
deploy it for themselves. 
I always advise students to be as honest and detailed as possible in your README.md file. 

Explain what works, what you didn't have time to do, what functionality you'd like to add in the
future, and what bugs you found and squashed along the way.
If you want, you can even separate your tests into a TESTING.md file if you
want to keep things a bit easier to read. A detailed README MD file can really
help the reader to get a feel for your project and your vision as a developer.
