# Monkees Project. 

This project is dedicated to a music band called The Monkees. This website will provide the users with information on the band
including a list of playable songs and a video with some information on their albums for reference. 

This website will be targeted towards exsiting Monkees fans and new fans that would like to book the band for any sort of 
events that required. The user will also be informed about the upcoming latest news and shows relating to the band. It will
also inform the users of breif history about the band and what makes them so great. 

## Home page. 
Gives an overview of the latest news and it informs the user that the band is available for bookings. The user has the option to join the mailing list for upto date news. Video avilable on the desktop and ipad versions.

## Music page.
Shows some of the monkees albums and a breif description of them including a music section where the user can play a few of their selected songs.

## Booking page.
Simple form where the user can place a booking for the band. 

## About us.
Breif history of the band and images of the band members included. 

## UX

This website is for exsiting Monkees fans as well as new ones that would like to book the band for events such as weddings birthdays etc.
The user would expect to receive news about the band and an idea of what music they would be expecting also they would expect the process of placing
a booking request to be simple and straight forward. This website achives this by clearly labling all the pages that the user can visit at the top
of the page in the order we would expect the user to navigate the page.

* A new Monkees fan would like to know the latest news on the band and can get this information on the home page. They will also be immediately informed that the band is available for bookings. The user would then be able to sign up for the mailing list for latest information sent to them via email. Since they are a new fan they may want to know what music they havent heard, so they can navigate to the music page get a description on each album and have a list of selected tracks to listen to. Once they are have an insight of the music they can the proceed to the booking page to make a request.

* A more seasoned Monkees fan or returning user would like to know the purpose of the website and to know how to book the band. This can be done on the home page through the link in the welcome section or through navigatig to the booking page to place a booking.

* A user would like to listen to some of the band music so they can know what music the band makes. They can do this by going on the music page and playing some of the selected tracks and they have a reference of albums that they can see.

Bellow you'll find a link that shows the initall design of the wire frames but as you can see the design has slightly changed.
For example i have decided to remove the search bar this is because it wouldnt have any functionality and the user can naviagte
to arears within the page that they require through the navbar. 

Also i decided to use the images of the band members on the about page only instead of everypage as this made the header section
look crowded now we have some space in between the navigation icons and the logo. 

[Wireframe](https://github.com/Harrysibbenga/Monkees_Project/blob/master/Wireframes/The%20Monkeys%20Wireframe.pdf)

## Features

### Exisiting features

* Social links - allows every user to visit The Monkees social media by clicking the link icons.
* Video - allows any user to play the video by clicking on the play button, comes with controls so the user can adjust volume and make the video full screen.
* Mailing list - allows users to input their email so they can sign up for the mailing list. If an incomplete email is entered a prompt is given.
* Music playback - allows any user to play and pause any song of their choice in the selected tracks section.
* Booking Form - any user can send an enquiry by filling out the form.
    * User can select a date or type one in manually
    * User is required to fill out the form or they wont be able to proceed. 
    * Numbers fields are strict to numbers. 
    * Email needs to have an @ symbol and .com or .co.uk

### Features left to implament

In the future I would like to implament the ability for the mailing list to send an email to the user once signed up to confirm that they are
on the mailing list and if they want to stop how they can do this.

Live updates on latest news. 

When user clicks a song all songs stop playing but the selected one.

Another feature would be to add functionality that enables the user to purchase the albums and merchandise directly from the website.

## Technologies used.

### Bootstrap 3.3.7.
* [Bootstrap](https://getbootstrap.com/docs/3.3/)
    * Used to create layout and styling using some of the classes and styles included in the framework.

### Font Awesome 4.7.0. 
* [Font Awesome](https://fontawesome.com/v4.7.0/)
    * Used for the link icons.

### Google Fonts
* [Google Fonts](https://fonts.google.com/)
    * Used for the fonts.

### Hover.css 2.1.1. 
* [Hover.css](http://ianlunn.github.io/Hover/)
    * Used to create hover effect in the nav.

## Testing 

1. Header
    1. Make sure when the mouse is hovering over the links the dropdown effect is visible.
    2. Make sure the fade effect is present on the social links when hovered.
    3. When the logo is clicked the user is taken to the home page.
    4. The active page has the active class on the navigation link displaying a solid background color making it easily distiguisable from the rest.

2. Home page
    1. Click the video buttons to play and stop the video.
    2. Mute button working.
    3. Click the maximise screen button to check that it is working.
    4. Download button works for downlading video.
    5. Sign up button clicked without any input error appears.
    6. Tried to submit without valid address error apprears. 
    7. Tried to submit with correct email address and the page returns to the top.
    8. Screen sizes bellow that of the tablets display the welcome section in one column.

3. Music Page
    1. Clicked play on the music player and pause.
    2. Mute button working
    3. Download button working.
    4. Scrolling working.
    5. Can play all songs together.
    6. Screen sizes over 1440px display the albums in one row
    7. Screen sizes for tablets and laptops display the albums in 2 rows of 2 albums per row.

4. Booking Form
    1. Submitted form with no inputs required me to fill out the required details
    2. Tried to input text in number forms error message appears
    3. Numbers are able to go into text arears.
    4. Email field required email format.
    5. All required fields must have values.
    6. Consistant on all screen sizes.

5. About Page
    1. Screen sizes less that the laptop width will not display the band members photos bellow the biography section. 

6. Responsive 
    1. Tested to see if all previous tests pass on different screen widths.
    2. Concluded that this was the case.

I noticed that once i submited the form it takes me to my email address and displays all the information in one line which will be hard to read.
I noticed that the number fields allowed be to input only one letter e however it wouldn't allow me to submit the form.

### Safari Vs Chrome
The website has scroll bars on safari whereas on chrome it fits perfectly.
The text in the navigation bar give a thinner look and feel compared to the ones in chrome.
Video hasnt got a center play button compared to chrome. 
The booking form on safari dosent support the email type.

### FireFox
Different video and music playbacks.
Fits perfectly like chome.
The music playback is aligned to the left compared to chrome and safaris which are alinged in the middle as expected.
Booking page supports the email type.

## Credits 

### Content
* Text in the about section was copied from [wikipedia](https://en.wikipedia.org/wiki/The_Monkees)

* Text for the albums where taken from the following 
    * Summer of love [recordpusher](https://recordpusher.com/products/copy-of-guthrie-arlo-alices-restaurant)
    * The Greatest Hits [wikipedia](https://en.wikipedia.org/wiki/Greatest_Hits_(1995_The_Monkees_album))
    * The Best Of The Monkees [wikipedia](https://en.wikipedia.org/wiki/The_Best_of_The_Monkees)
    * More Greatest Hits Of The Monkees [wikividly](https://wikivividly.com/wiki/More_Greatest_Hits_of_The_Monkees)

* Text for the latest news about the band was taken from [The Monkees](https://www.monkees.com/)

### Media
* The media was taken from [github](https://github.com/Code-Institute-Org/project-assets/tree/master/stream-1/band-assets)

* The summer of love image was taken from [here](https://imagescdn.juno.co.uk/full/CS654754-01A-BIG.jpg) 

* The logo image was taken from [wikimedia](https://commons.wikimedia.org/wiki/File:Monkees-logo.png)


## Published website. https://harrysibbenga.github.io/Monkees_Project/

