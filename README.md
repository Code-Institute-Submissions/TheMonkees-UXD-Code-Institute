# TheMonkees-UXD-Code-Institute

The Monkees is a 1960s band that is still touring today, with over 50 years of experience in the music industry and performing live shows. The Monkees now wish to establish an online presence to promote their music, social media and the option to book The Monkees to perform at a venue.

You can view the website [here](https://msped.github.io/TheMonkees-UXD-Code-Institute/) using GitHub pages.

## UX

The website is to be used by new fans and established fans. 

Users would like to: 

- Listen to The Monkees catalogue of music. 
- See up-coming tour dates with link to purchase tickets from a third-party site.
- Provide social links for fans.
- Be able to book The Monkees for events using an online form.

As well as the fans using the site it will be used to promote The Monkees as a business.  

Initial Wireframes for the site:

- Desktop: [Home](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Monkees%20Home%20-%20Desktop.png) | [Tour Dates](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Tour%20Dates%20-%20Desktop.png) | [Booking](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Booking%20-%20Desktop.png) 

- Mobile: [Home](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Monkees%20Home%20-%20Mobile.png) | [Tour Dates](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Tour%20Dates%20-%20Mobile.png) | [Booking](https://github.com/msped/TheMonkees-UXD-Code-Institute/blob/master/Designs/Booking%20-%20Mobile.png) 

## Features

### Exisiting Features

- Music & Videos - This allows users to play, in browser, the music and Music Videos by The Monkees, past or present.

- Full Width, mobile friendly navigation menu - A navigation Menu that will collapse down when the resolution reduces, making a user-friendly experience no matter what device the user is on. 

- Booking - Fans and venues will be able to book The Monkees using a simple, user-friendly online form on the website.

- Tour Dates - Tours Dates will list the tour dates for The Monkees upcoming tour with links to a third-party ticket purchasing site. 

- Social Links - The Monkees social links have been added to the bottom of each page to keep consistencey throughout the site to increase social following and make it easily locatable for new fans. 

### Features Left to Implement

- A search function throughout the site to help users locate information they require easily.
- Implement a fan forum for fans to share memories, covers and have a general chat with fellow fans.
- Soundcloud/Spotify API for automatic updates when new music is released.
- Back End functionality to modify Tour Dates and Latest News without the need for a developer each time a modification is required. 

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - HTML5 was used for the semantic structure and presenting the content of the webapge.

 - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - CSS3 was used for the styling of the content to produce an aesthetically pleasing viewing experience.

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap provides responsives layouts and components such as the navigation menu for quick, easy, efficient web development, all in a mobile-first approach.

- [Font Awesome](https://fontawesome.com/)
    - Font Awesome was used for the social links, mainly the social media icons for a professional finish.

## Testing

Below is testing conducted on the website.

- Testing the Booking form
    1. Click on 'Booking' in the navigation bar.
    2. First I clicked the 'Send Request' button - As expected, no request was sent as no information was filled in.
    3. After filling in the form I clicked the 'Send Request' button again, this time the submission was successful. This is noted by the information appearing in the URL. 
    4. As a further measure I filled out the form but then removed the @ symbol from the e-mail address. As expected the form failed to sumbit due to incorrect formatting of the e-mail address.

- Testing links betweens pages  
    For this section I tested all of the links between the pages, navigation bar and and links built into the page. Testing all of the links resulted in everything linking to another page in the website working as intended by staying within the tab. 

    All links to which the user is directed to another site opened in a seperate browser tab. These links include social site and the third-party ticket purhcasing site. 


- Issues discovered while testing and how they were rectified.

    1. Issues number one was that on Microsft Edge jQuery script wasn't being pulled through due to the link not using a secure https connection from the jQuery CDN. Since jQuery was loading in, in a mobile view the button to use toggle the navigation wasn't working. The issue was rectified by using Googles jQuery API.
    
    2. Issue number two was on Microsoft Edge and Github Pages for other users the font Caevet wasn't loading in. After checking the main.css file I found that the `@font-face` source was looking at a different folder so therefore wasn't loading in and given a 404 error in the console. This was rectified by inputting the correct file path `../assets/Fonts/Caveat-Regular.ttf`

For testing the responsive aspect of the website I used a Google Chrome Extension called [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) to resize the  Google Chrome Window to various device sizes.

Validating the code was done with the help of [Freeformatter.com](https://www.freeformatter.com/html-validator.html) and validating of the CSS was done with the help of [W3C CSS Validation Service, Jigsaw](https://jigsaw.w3.org/css-validator/)

This website is currently viewable with no deployment issues in:

- Google Chrome
- Edge/IE

[Visual Studio Code](https://code.visualstudio.com/) was the editor that I used in the coding of the website. While using Visual Studio Code I used an extension pack called LiveServer to run the website on my local machine for testing.


## Depolyment

The website was deployed using Github Pages, you can view it [here](https://msped.github.io/TheMonkees-UXD-Code-Institute/). 

## Credits

### Content

- The text for 'About the Band' on the Home page was copied from a [biography](https://www.allmusic.com/artist/the-monkees-mn0000478603/biography) written by Mark Deming for AllMusic.

- News articles and the information were taken from the [Official Monkees Site](https://www.monkees.com/news).

### Media 

- The photos, music and music video were obtained from [The Code Institue](https://github.com/Code-Institute-Org/project-assets).

