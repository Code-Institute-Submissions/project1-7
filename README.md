# Project 1
Build a website for a band called Cult of Luna. It provides information about the band, their music, tour dates, means of contact, and social media presence.
## UX
Their official website is very minimalistic (and also have changed a bit since I started the project) and I wanted to create something that will offer a user more information and also showcase their music.  
  
It consists of six sections.  
The about section displays an image of the band members and also provides information about the music they create.  
The photos section.  
The music section which displays their albums and also have a Spotify player embedded.  
The video section which contains a video from a concert.  
The tour section displays all their future shows and provides links to websites where the tickets can be bought.  
The contact section provides a newsletter sign up form and a contact email address.  
The footer contains links to social media sites.

## Technologies
* HTML
* CSS
* Bootstrap (4.3.1)
* Google Fonts
* Font Awesome icons
## Features
* Bootstrap
  * Navbar
  * ScrollSpy
  * Modal (About section)
  * Grid (Music, Tour and Contact sections)
  * Carousel (Photos section)
* Players
  * Spotify
  * Youtube
* Javascript
  * Navbar menu collapses after clicking a link
  * Changing a newsletter input field after clicking submit
### Features left to implement
* Background video on the landing page
* Replace CSS hover on albums with an onclick Javascript event which works both on desktop and mobile
* Parallax scrolling
## Testing
The website was tested on Firefox and Chrome browsers (both desktop and mobile) at various resolutions to make sure the website provides a consistent layout.
All links, buttons and a submit form have been manually tested to ensure they work as intended.  
  
I have tried to make the website as responsive as possible, so that it will look good in different resolutions. For example, in the music section the size and the number of albums displayed horizontally are determined by resolution, with 4 albums displayed on large screens, 2 on medium, and on smaller screens the albums are stacked, displaying just one.
Also the size and formatting of various elements depend on resolution.
  
I have discovered that the embedded YouTube video doesn't work on a local machine, but it works when the website is deployed on the server. Turns out there are some videos that YouTube doesn't allow you to play locally.

## Deployment
This website is deployed on GitHub Pages: https://m-sbt.github.io/project1/  
To run locally, you can download a ZIP file or clone it by pasting `git clone https://github.com/m-sbt/project1.git` into the terminal.
## Credits
### Content
About section information: [link](https://en.wikipedia.org/wiki/Cult_of_Luna)
### Media
Landing view image: [link](https://www.behance.net/gallery/57198371/Cult-Of-Luna-Years-in-a-Day)  
About section image: [link](https://www.provinssi.fi/performer/cult-of-luna)  
Photos: [link](https://twitter.com/Cultofluna_off)
### Acknowledgements
Responsive Spotify player: [link](http://jsfiddle.net/JMPerez/qa73L/)  
Blur image on hover and display text: [link](https://stackoverflow.com/questions/52846599/html-blur-image-on-hover-w-text/52847870#52847870)  
Text fadeIn effect: [link](https://www.tutorialspoint.com/css/css_animation_fade_in.htm)
