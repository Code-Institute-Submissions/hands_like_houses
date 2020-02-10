# Hands like houses band website

The Hands like houses website was created so users can have a central place to find all the latest information,
updates, news and videos from the band, as well as having somewhere to find out show dates and purchase tickets 
and band merchandise. 

## UX

The website is primarily aimed at users who follow the bands progress and music, to give them somewhere to get all of the band's updates
quickly and easily. secondly it's aimed at users who are new to the band and are looking to find out more about them and their music,
and lastly it is aimed at people/organisations looking to book the band for shows.

The home page is designed to contain snippets of only the very latest updates, with each section having a call to action button
below which will transport the user to a separate page which contains further information related to that snippet in the home page section.
The desktop contains a navbar at the top of the screen (not fixed) with the current page clearly highlighted so the user knows where
they are on the site. The mobile version has a navbar that is fixed to the top of the screen where the page list is collapsed into
a burger button, as this is a standard for mobile websites and has the aim of the user learning the navigation quickly.

#### User story:
I am a fan on the band and I want to find out when and where the next shows will be so I can possibly purchase a ticket for a show near me.
The latest 2 shows are shown on the homepage with a link to the shows page at the bottom. The shows page contains information on all of
the bands upcoming shows and contains a button to take you to an external site where you would be able to purchase tickets.

#### User story:
I have recently heard a song by the band and would like to find out more about them and hear more of their music.
The band page has information on the band as a whole and also lists all the members of the band so you can see who is who.
The media page contains videos of the bands latest music videos and also all of their albums, which have a call to action below each
which will take you to an external site so you can potentially purchase an album.

#### User story:
I organize shows for a living and I'm looking to contact the band to discuss some opportunities I have at the moment and potentially 
book them for a show.
This can be done by going to the "Bookings" tab which contains a userform where you will be able to send the band some details online
the event as well as leaving your contact details, if the band are interested in the event they will get in touch with you.

The wireframes/initial mockups for the band website can be found here: https://github.com/Matte-gtr/hands_like_houses/tree/master/wireframes

## Features
Home Page - This contains snippets of the latest videos, albums and news, each with a button at the bottom of the section which will 
take you to the correct page to find out more about that particular area.

* Band page - This page contains information/background about the band also lists a photo of each member with their name and role in the band.

* Shows - This contains all of the bands upcoming shows along with the date of the show, the location, the venue and a button to tke you
to an external site to purchase a ticket.

* Media - This contains the latest music videos released by the band and also the album section which contains the covers of all albums that
the band has for sale with buttons below each to take you to an external site to purchase the album.

* Gallery - This contains various images of the band which you can click on to enlarge them and scroll through all the images.

* Shop - This contains all the items of clothing/merchandise that the band has for sale with their prices and buttons to take you
to an external site to purchase the item.

* Bookings - This contains a userform which will allow you to message the band if you are interested in discussing booking them for a show.

## Existing Features

#### Navbar:
This allows the user to move around the site. On a mobile/small screen, it collapses into a burger button which contains a list of all 
the page links.
#### Call to action buttons on the home page:
When clicked, these will take you to the relevant page 
#### Youtube videos:
User can hear/view the bands latest videos by clicking play on the youtube iframe.
#### Image viewer:
The gallery page uses Fancybox image view to enlarge an image when you click on it, then scroll through them left left/right buttons.
#### Contact form:
If the user fills in the fields on the bookings page it will allow them to send their request to the band if they click "send".

## Features left to implement:

Links on the band members section to find more information on each member of the band.

video clips added to the gallery section.

## Technologies Used

HTML5

CSS3

Bootstrap
https://getbootstrap.com/docs/4.4/getting-started/introduction/
Bootstrap was used to speed up the development time and make use of their grid system for responsive mobile first design.

Google fonts
https://fonts.google.com/
Google fonts was used to provide all the fonts for the site as they have a very large library of fonts

Fancybox image viewer
http://fancybox.net/
This was used to create an user friendly way to view all the gallery images

Youtube
https://www.youtube.com/
Youtube was used to host the band videos and then link to them using an iframe. Youtube offers the easiest way of adding a video to you website.

JavaScript (Bootstrap and fancybox)

JQuery
The project uses JQuery to simplify DOM manipulation.

## Testing

During the creation of this project, Google Chrome developer tools was used to view the site/pages on various different devices.
The developer tools displays used were: Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 5/se, iPhone X, iPhone 6/7/8, iPhone 6/7/8 Plus, iPad, iPad Pro.
These were checked at multiple points throughout the development and then once again on all the above devices when the project was completed.

The site was also tested on various actual devices listed below once the site was completed:
* Asus Laptop
* Lenovo desktop
* Samsung Galaxy A5
* iPhone 8
* Sansung Galaxy S9
* Samsung tablet

The site was then tested on 3 different browsers:
* Google Chrome
* Internet Explorer
* Mozilla Firefox

The display on internet explorer had some differences in font size but the site still generally flowed quite well.

The site was also tested for fast user learning by asking 3 different people to use the site and find a particular section, then asking
them how they felt about how easy it was to find. The reaction was good across all the testers.

#### Bookings form:
The first 3 fields have to be filled in before the form can be submitted. This was the case across all the different browsers.
The form is not linked to anything so an errors appears on submission, to update at a later date.
The form felt usable on all the different devices through testing and sizes well across all the screen sizes.

##### Fancybox image viewer:
This was also tested on all the different devices and works well across all of them. All of the options to scroll through 
images worked on the different devices they were tested on.

#### Footer mailing list form:
This is not able to be submitted until an email address is filled in. This was the case in the testing across all of the devices.

## Deployment
Github pages
This site was deployed using Github pages.
As the site was created in github originally and then worked on in Gitpod, a repository had already been created, then once the 
site was mostly complete, the code
was pushed to the github repository.
I then went into the github repository, clicked on settings, scrolled down to the Github pages section and selected master branch 
in the Source dropdown. this deploys the site 
and when it updates, provides a link to the site.

If you would like to edit or improve this website, type the following into your development evironment terminal after ensuring you are
in the correct folder:
git clone "https://github.com/Matte-gtr/hands_like_houses"
This will copy all of the files into you workspace and allow you to edit them as you see fit.

#### Credits
youtube - video hosting

#### photo credits:
background concrete image: pinterest/rawpixel
hands like houses official website
design cuts
alison toon
noted name
The daily listening
soundcheck live
youtube
skiddle.com
forbes.com
upset magazine
freepik
shutterstock

#### Content
kerrang - news excerpts / links
bandsintown.com - ticket link
about the band - wikipedia

The inspiration for this site primarily came from the ACDC band website.