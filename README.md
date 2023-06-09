# ZestHouse Juice Bar

(Developer: Martyna Nowak)

The ZestHouse Juice Bar website is designed to be accessible and responsive on all devices. It allows easy access to a menu with prices, opening times, gallery, and information about the venue.

![an image of the webpage opened on different devices from amiresponsive](docs/features/amiresponsive.jpg)

[Live webpage](https://mmnowak.github.io/zesthouse/)

---

## Table of Content

1. [Project Goals](#project-goals)
    1. [Overview](#overview)
    2. [Goals](#goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    1. [User Requirements and Expectations](#user-requirements-and-expectations)
    2. [User Stories](#user-stories)
3. [Design](#design)
    1. [Colour scheme](#colour-scheme)
    2. [Typography](#typography)
    3. [Imagery](#imagery)
    4. [Wireframes](#wireframes)
4. [Features](#features)
5. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks and Tools](#frameworks-and-tools)
6. [Testing](#testing)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Accessibility](#accessibility-testing)
    4. [Performance](#performance)
    5. [Device testing](#performance-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatibility)
    7. [Testing user stories](#testing-user-stories)
7. [Credits](#credits)
    1. [Media](#media)
    2. [Code used](#code-used)
    3. [Content](#content)
8. [Bugs](#bugs)
9. [Deployment](#deployment)
11. [Acknowledgements](#acknowledgements)

## Project Goals

### Overview

The main purpose of the project is to create an easy-to-use and visually appealing website for ZestHouse Juice Bar, a venue serving healthy drinks and snacks. The website is supposed to feature important information, such as prices, opening times, and available facilities. It is designed to be user-friendly and concise.

### Goals

1. A website that can be navigated easily and intuitively.
2. Easy access to the drink and food menu and prices.
3. A visual representation of the products.
4. Clearly presented information about the venue and available facilities.
5. Easy access for the user to contact the venue with questions and feedback.
6. A clean design that catches the eye and represents the general 'vibe' of the venue.
7. A website that looks good and responds correctly on all device sizes.
8. A website that is accessible to all users.

## User Experience

### Target Audience
* All age groups;
* Health-conscious people;
* People wanting to buy delicious drinks, either to sit in or takeaway;
* People looking for a venue to remote work at;
* Groups looking for a venue that can be booked for events.

### User Requirements and Expectations
1. Links and buttons that work as expected.
2. A simple and intuitive navigation system.
3. Information presented in clear and concise manner.
4. Visually appealing design.
5. Easy way to submit questions and feedback.
6. Accessibility.

### User Stories

#### First-time Visitor
1.	As a first-time user, I want to know what products the ZestHouse is selling.
2.	As a first-time user, I want to know the prices.
3.	As a first-time user, I want to know the location.
4.	As a first-time user, I want to know the opening times.
5.	As a first-time user, I want to know the facilities available.
6.	As a first-time user, I want to easily contact the venue with any questions I might have.
7.	As a first-time user, I want to know more about the venue and its history.

#### Returning Visitor
8.	As a returning user, I want to be able to send my feedback easily.
9.	As a returning user, I want to find the ZestHouse on social media.
10.	As a returning user, I want to see photos from past events held at the venue that I attended.

#### Site Owner
11.	As the site owner, I want the users to be able to view the site on a range of device sizes.
12.	As the site owner, I want to make it easy for potential customers to see the facilities and features available.
13.	As the site owner, I want to allow customers to contact ZestHouse with their questions or feedback.
14.	As the site owner, I want the users to easily find our menu and prices.
15.	As the site owner, I want the users to be directed back to the homepage should they come across a 404 error.
16.	As the site owner, I want the users to feel their questions and feedback are most welcome.
17.	As the site owner, I want the customers to easily find directions to the venue.
18. As the site owner, I want the users to be able to navigate the website easily.

## Design

### Colour Scheme
![The colour palette](docs/features/palette.png)

Two of the colours (#c92324 and #ea861a) used were chosen using a colour picker from the background image (see the Imagery section below). Then a [colour palette generator](http://colormind.io/bootstrap/) was used to choose complimentary colours (#084208 and #f4f7f9). [The contrast checker](https://webaim.org/resources/contrastchecker/) showed that the contrast between the navbar background and text is good (ratio 10.88:1). However, the contrast ratio was too low for the colours used for the main paragraphs (#ea861a for the background and #084208 for the text). Thus, to improve accessibility, a lighter colour (#f2d363) was chosen for the background, bringing the contrast ratio score to 7.96:1.


### Typography

The fonts used for the website are imported from [Google Fonts](https://fonts.google.com/).
The font chosen for the logo as well as all the headings is Viga. It is described as having a good performance on the screen as well as a great personality.

![A font sample](docs/features/fontviga.png)

A [font pairing website](http://www.ourownthing.co.uk/fontpairing/) was then used to pick Anek Bangla, the font used for all the other text, such as paragraphs and buttons.

![A font sample](docs/features/fontanek.png)

### Imagery

The image main image, used for the background, was chosen due to its vibrant colours and the fruit looking like it is bursting with flavour and vitamins. It is supposed to be associated with concepts such as freshness, nutrition, health and wellness. 

![halved oranges and pomagranates](docs/features/citrussmall.jpg)

### Wireframes

Wireframes were created for mobile and desktop using Balsamiq software.

<details><summary>Index Page</summary>
<img src="docs/wireframes/mp1mobilehero.png">
<img src="docs/wireframes/mp1deskophero.png">
</details>

<details><summary>About Us Page</summary>
<img src="docs/wireframes/mp1mobilecarusel.png">
<img src="docs/wireframes/mp1deskopcarusel.png">
</details>

<details><summary>Gallery Page</summary>
<img src="docs/wireframes/mp1gallerydeskop.png">
<img src="docs/wireframes/mp1gallerymobile.png">
</details>

<details><summary>Menu Page</summary>
<img src="docs/wireframes/mp1menudeskop.png">
<img src="docs/wireframes/mp1menumobile.png">
</details>


<details><summary>Contact Us Page</summary>
<img src="docs/wireframes/mp1mobileform.png">
<img src="docs/wireframes/mp1deskopform.png">
</details>

## Features

### Logo and Navigation bar
* Featured on all pages, the navigation bar is fully responsive and changes to a burger toggler menu on smaller screens.
* The left of the navigation bar features a logo, which when clicked on leads to the index page. The right side contains links to the Home Page, About Us Page, Gallery, Menu Page and Contact Us Page.
* The link to the page the user is currently on is indicated by a different colour background.
* User stories covered: 11, 18.
![footer as seen on deskop](docs/features/navbar.png)
![footer as seen on mobile](docs/features/navbarmobile.png)

### Footer
* Featured on all pages.
* Contains three sections: contact details, social media links and opening times.
* Social media links are represented by easily identified icons.
* User stories covered: 4, 6, 9.
![footer as seen on deskop](docs/features/footer.png)
![footer as seen on mobile](docs/features/footermobile.png)

### Index Page
* Features a short text introducing the venue.
* Includes two call-to-action buttons, leading to the Menu page and About Us Page.
*  User stories covered: 11, 18

![two call-to-action buttons](docs/features/indexbuttons.png)

### About Us Page
* Includes a paragraph introducing the owners and the idea behind the business.
![about us page](docs/features/about.png)
* Features description of facilities available, accompanied by relevant pictures.
![facilities section](docs/features/facilities.png)
* Includes the venue location on an embedded Google Map.
![the map on the about us page](docs/features/map.png)
* User stories covered: 3, 5, 7, 12.

### Gallery Page
* A masonry-style picture gallery. Arranged in three columns on large- and medium-sized devices, and a single column on small screens.
* User stories covered: 10, 11.
![gallery page](docs/features/gallery.png)

### Menu Page
* The menu overview takes the form of a carousel containing cards, each card representing a menu section with a corresponding title and image. It shows three cards per slide on medium and large devices and one card per slide on small devices. It contains nine sections (Cold pressed juices, tropical juices, smoothies, smoothie bowls, juice shots, slushies, hot drinks, alcoholic drinks and snacks). 
* Allows the user to navigate via back and forward arrows, located at the top on small screens and at the sides on medium and large screens.

![Menu carousel on deskop](docs/features/menupagecarousel.jpg)
![Menu carousel on mobile](docs/features/menupagecarouselmobile.png)
* Clicking the 'see prices' button for each card leads to a price menu. This allows the user to quickly locate prices of items they are interested in.
![price menu](docs/features/menu.png)
* A back-to-top button in the bottom right corner of the price menus leads back to the carousel with menu sections. It allows the user to navigate the menu easier and quicker. The back-to-top option is represented by a commonly identified icon.

![back-to-top-button](docs/features/scrollup.png)

* User stories covered: 1, 2, 11, 14, 18.

### Contact Us Page
* Features a contact form which allows the user to easily contact the venue with any questions or feedback.
![the contact form](docs/features/form.png) 
* Contains contact details such as an address, a phone number and an email address.

![Contact info](docs/features/contact.png)

* User stories covered: 3, 6, 8, 13.

### Thank You Page
* A message thanks the user for submitting the contact form.
* Has a 'go back' button leading back to the contact.html page.
* User stories covered: 16.

![thank you page](docs/features/thankyoupage.png)

### 404
* Custom error page which contains a button leading back to the index page.
* User stories covered: 15, 18.

![404 page](docs/features/404.png)


### Accessibility
The following steps were taken to ensure the website is accessible:
* A contrast checker tool was used when deciding on the colour palette to ensure a sufficient colour contrast throughout the page.
* Aria-labels were added to the icons to enable screen readers to understand them.
* Aria-current was used to indicate the current page for screen readers.
* All images are attributed with alternative descriptions.
* Sans serif fonts were chosen to ensure the website is dyslexia-friendly.
* Semantic HTML was used.

## Technologies Used

### Languages

* [HTML](https://en.wikipedia.org/wiki/HTML)
* [CSS](https://en.wikipedia.org/wiki/CSS)

### Frameworks and Tools

* [Bootstrap](https://getbootstrap.com/)
* [Balsamiq](https://balsamiq.com/wireframes/)
* [GitHub](https://github.com/)
* [GitPod](https://www.gitpod.io/)
* [Google Fonts](https://fonts.google.com/)
* [Colormind.io](http://colormind.io/)
* [Webaim.org Contrast Checker](https://webaim.org/)
* [Hover.css by Ian Lunn](https://ianlunn.github.io/Hover/)
* [FontAwesome](https://fontawesome.com/)

## Testing

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. No errors were found.

See scores:

[Index.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Findex.html)

[About.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Fabout.html)

[Gallery.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Fgallery.html)

[Menu.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Fmenu.html)

[Contact.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Fcontact.html)

[Thank-you.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2Fthank-you.html)

[404.html](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmmnowak.github.io%2Fzesthouse%2F404.html)

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the css file for the website via file upload. No errors were found.
![CSS Validation score](docs/features/cssvalidation.png)

### Accessibility Testing
The WAVE web accessibility evaluation tool by WebAIM was used to ensure the website is fully accessible.

See scores:

[Index.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/index.html)

[About.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/about.html)

[Gallery.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/gallery.html)

[Menu.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/menu.html)

[Contact.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/contact.html)

[Thank-you.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/thank-you.html)

[404.html](https://wave.webaim.org/report#/https://mmnowak.github.io/zesthouse/404.html)


### Performance

Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. Three pages received a good score in all categories:

<details><summary>Index Page</summary>
<img src="docs/features/lighthouseindex.png">
</details>

<details><summary>Gallery Page</summary>
<img src="docs/features/lighthousegallery.png">
</details>

<details><summary>Contact Us Page</summary>
<img src="docs/features/lighthousecontact.png">
</details>

The remaining pages scored good in Accessibility, Best Practices, and SEO categories and average in Performance. I have taken some steps to improve the performance, such as changing all images to either avif or webp format, however the score still remained in the average bracket. This could be due to additional libraries, such as Bootstrap, being installed.

<details><summary>About us Page</summary>
<img src="docs/features/lighthouseabout.png">
</details>

<details><summary>Menu Page</summary>
<img src="docs/features/lighthousemenu.png">
</details>

<details><summary>404 Page</summary>
<img src="docs/features/lighthouse404.png">
</details>

<details><summary>Thank You Page</summary>
<img src="docs/features/lighthousethankyou.png">
</details>

<details><summary>These are factors lowering down the score:</summary>
<img src="docs/features/lighthousediag.png">
</details>

### Performance tests on various devices

The website was used on the following devices:
* Thinkpad Yoga 460
* Xiaomi 11 Lite

As well as on all available device options when using Google Chrome Developer tools.

See examples:

<details><summary>Small screen: Iphone 5</summary>
<img src="docs/features/testingiphone5.png">
</details>

<details><summary>Medium screen: Ipad Mini</summary>
<img src="docs/features/testingipadmini.png">
</details>

### Browser compatibility

The website was tested on the following browsers:

* Google Chrome
* Opera
* Microsoft Edge

### Testing user stories

#### First-time User Goals

1. As a first-time user, I want to know what products the ZestHouse is selling.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Menu | Navigate to the menu page | See the product list | Works as expected |
| Button | Click on the 'See Menu' button on the menu page | Go to the menu | Works as expected |

<details><summary>Find Menu Page</summary>
<img src="docs/gifs/menubutton.gif">
</details>

2. As a first-time user, I want to know the prices.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Menu | Navigate to the menu page | See the prices | Works as expected |
| Button | Click on the 'See Menu' button on the menu page | Go to the menu | Works as expected |

<details><summary>Find the prices</summary>
<img src="docs/gifs/pricesbutton.gif">

<img src="docs/gifs/priceslink.gif">
</details>

3.	As a first-time user, I want to know the location.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| About Us | Navigate to the about us page and scroll down | Locate the map | Works as expected |
| Contact Us | Navigate to the contact us page | Find the address | Works as expected |

<details><summary>Find the map</summary>
<img src="docs/gifs/map.gif">
</details>
<details><summary>Find the address</summary>
<img src="docs/gifs/address.gif">
</details>

4.	As a first-time user, I want to know opening times.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Footer | Locate the footer | See the opening times | Works as expected |

<details><summary>Find the opening times</summary>
<img src="docs/gifs/openingtimes.gif">
</details>

5.	As a first-time user, I want to know the facilities available.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| About us | Navigate to the About us page | Scroll down to the facilities section | Works as expected |

<details><summary>Find the facilities section</summary>
<img src="docs/gifs/facilities.gif">
</details>

6.	As a first-time user, I want to easily contact the venue with any questions I might have.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Contact us | Navigate to the Contact us page | Use the form to submit a message | Works as expected |
| Contact us | Navigate to the Contact us page | Click on the email address to send email | Works as expected |
| Contact us | Navigate to the Contact us page | Click on the phone number to call | Works as expected |
| Footer | Locate the footer | Click on the email address to send email | Works as expected |
| Footer | Locate the footer | Click on the phone number to call | Works as expected |

<details><summary>Use the form</summary>
<img src="docs/gifs/contactform.gif">
</details>

<details><summary>Send email</summary>
<img src="docs/gifs/emailbox.gif">

<img src="docs/gifs/emailfooter.gif">
</details>

<details><summary>Make a call</summary>
<img src="docs/gifs/phonebox.gif">

<img src="docs/gifs/phonefooter.gif">
</details>

7.	As a first-time user, I want to know more about the venue and its history.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Button | Click on the 'Our Story' button on the menu page | Go to the About us page | Works as expected |
| Index Page | Open the index page | Find the summary paragraph | Works as expected |
| About us | Navigate to the About us page | Locate the Our Story section | Works as expected |

<details><summary>Find the About Us page</summary>
<img src="docs/gifs/aboutus.gif">
</details>

#### Returning User 

8.	As a returning user, I want to be able to send my feedback easily.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Contact us | Navigate to the Contact us page | Use the form to submit a message | Works as expected |
| Contact us | Navigate to the Contact us page | Click on the email address to send email | Works as expected |
| Footer | Locate the footer | Click on the email address to send email | Works as expected |

<details><summary>Use the form</summary>
<img src="docs/gifs/contactform.gif">
</details>

<details><summary>Send email</summary>
<img src="docs/gifs/emailbox.gif">

<img src="docs/gifs/emailfooter.gif">
</details>

<details><summary>Make a call</summary>
<img src="docs/gifs/phonebox.gif">

<img src="docs/gifs/phonefooter.gif">
</details>

9.	As a returning user, I want to find the venue on social media.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Footer | Locate the footer | Click on the social media icons | Works as expected |

<details><summary>Find the social media section</summary>
<img src="docs/gifs/socialmedia.gif">
</details>

10.	As a returning user, I want to see photos from past events held at the venue that I attended.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Gallery | Navigate to the gallery page | View gallery images | Works as expected |

<details><summary>Find the gallery</summary>
<img src="docs/gifs/gallery.gif">
</details>

#### Site owner goals

11.	As the site owner, I want the users to be able to view the site on a range of device sizes.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Navigation bar | Open any link | Go to desired page and view on device | Works as expected |

12.	As the site owner, I want to make it easy for potential customers to see the facilities and features available.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| About us | Navigate to the About us page | Scroll down to the facilities section | Works as expected |

<details><summary>Find the facilities section</summary>
<img src="docs/gifs/facilities.gif">
</details>

13.	As the site owner, I want to allow customers to contact ZestHouse with their questions or feedback.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Contact us | Navigate to the Contact us page | Use the form to submit a message | Works as expected |
| Contact us | Navigate to the Contact us page | Click on the email address to send email | Works as expected |
| Contact us | Navigate to the Contact us page | Click on the phone number to call | Works as expected |
| Footer | Locate the footer | Click on the email address to send email | Works as expected |
| Footer | Locate the footer | Click on the phone number to call | Works as expected |

<details><summary>Use the form</summary>
<img src="docs/gifs/contactform.gif">
</details>

<details><summary>Send email</summary>
<img src="docs/gifs/emailbox.gif">

<img src="docs/gifs/emailfooter.gif">
</details>

<details><summary>Make a call</summary>
<img src="docs/gifs/phonebox.gif">

<img src="docs/gifs/phonefooter.gif">
</details>

14.	As the site owner, I want the users to easily find our menu and prices.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Menu | Navigate to the menu page | See the product list | Works as expected |
| Menu | Navigate to the menu page | See the prices | Works as expected |
| Button | Click on the 'See Menu' button on the menu page | Go to the menu | Works as expected |

<details><summary>Find the prices</summary>
<img src="docs/gifs/pricesbutton.gif">

<img src="docs/gifs/priceslink.gif">
</details>

15.	As the site owner, I want the users to be directed back to the homepage should they come across a 404 error.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Go back button | Click on the 'go back' button on the 404 error page | Find the homepage | Works as expected |
| Logo | Click on the logo to navigate back to the index page | Find the homepage | Works as expected |
| Logo | Click on the logo to navigate back to the index page | Find the homepage | Works as expected |
| Navigation bar | Click any link to navigate back to desired page | Find desired page | Works as expected |

<details><summary>Go back from the 404 page</summary>
<img src="docs/gifs/404button.gif">

<img src="docs/gifs/404logo.gif">
</details>


16.	As the site owner, I want the users to feel their questions and feedback are most welcome.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Thank you page | Submit a message using the form | See the 'thank you' message | Works as expected |

<details><summary>See a Thankyou Page</summary>
<img src="docs/gifs/thankyou.gif">
</details>

17.	As the site owner, I want the customers to easily find directions to the venue.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| About Us | Navigate to the about us page and scroll down | Locate the map | Works as expected |
| Contact Us | Navigate to the contact us page | Find the address | Works as expected |

<details><summary>Find the map</summary>
<img src="docs/gifs/map.gif">
</details>
<details><summary>Find the address</summary>
<img src="docs/gifs/address.gif">
</details>

18. As the site owner, I want the users to be able to navigate the website easily.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|:-----------:|:----------:|:-------------------:|:-----------------:|
| Navigation bar | Click any link to go to desired page | Find desired page | Works as expected |
| Call to action buttons | Click on the buttons to go to a relevant page or section | Find the relevant page or section | Works as expected |
| Back-to-top button on the menu page| Click on the button to go back to the menu overview | Scroll up | Works as expected |

<details><summary>Back-to-top button</summary>
<img src="docs/gifs/scrollup.gif">
</details>

## Credits

### Media

The main image, used for the background, is by [Engin Akyurt on Unsplash](https://unsplash.com/photos/drzu0uPgmoU)

#### About Us Page
[Photo by Alexas Fotos on Pexels](https://www.pexels.com/photo/close-up-photo-of-stacked-tissue-rolls-10760874/)

[Photo by OVAN on Pexels](https://www.pexels.com/photo/person-sitting-facing-laptop-computer-with-sketch-pad-57690/)

[Photo by Ivan Samkov on Pexels](https://www.pexels.com/photo/people-celebrating-a-little-girl-s-birthday-7922014/)

#### Menu Page
[Photo by Pranjall Kumar on Pexels](https://www.pexels.com/photo/red-juice-in-glasses-8600079/)

[Photo by Studio Naae on Pexels](https://www.pexels.com/photo/close-up-shot-of-a-glass-of-fruit-juice-13546345/)

[Photo by Brenda Godinez on Unsplash](https://unsplash.com/s/photos/smoothie?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

[Photo by Vicky Ng on Unsplash](https://unsplash.com/s/photos/smoothie-bowl?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

[Photo by Toa Heftiba on Unsplash](https://unsplash.com/s/photos/juice-shots?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

[Photo by Mwabonje on Pexels](https://www.pexels.com/photo/close-up-photo-of-latte-art-1714950/)

[Photo by The Castlebar on Pexels](https://www.pexels.com/photo/close-up-shot-of-glasses-of-cocktails-9201052/)

[Photo by Roberto Shumski on Pexels](https://www.pexels.com/photo/snack-foods-on-round-wooden-tray-9134584/)

[Photo by Melissa Walker Horn on Unsplash](https://unsplash.com/photos/ptvKywiTghw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

#### Gallery Page
[Photo by Brooke Lark on Unsplash](https://unsplash.com/photos/t7wg7BJU2-s)

[Photo by Farhad Ibrahimzade on Unsplash](https://unsplash.com/photos/CiDpRQ9oPso)

[Photo by Whitney Wright on Unsplash](https://unsplash.com/photos/TgQkxQc-t_U)

[Photo by Louis Hansel on Unsplash](https://unsplash.com/photos/BT2hIfR5oj8)

[Photo by Marc Babin on Unsplash](https://unsplash.com/photos/22fsBrruHPQ)

[Photo by Louis Hansel on Unsplash](https://unsplash.com/photos/S3E8Y_SRPUw)

[Photo by Louis Hansel on Unsplash](https://unsplash.com/photos/H7Lti8qa0dE?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

[Photo by Louis Hansel on Unsplash](https://unsplash.com/photos/byzvm4J8Ljw)

[Photo by Helena Yankovska on Unsplash](https://unsplash.com/photos/7EbGkOm8pWM)

### Code Used
* The HTML for the [navigation bar](https://getbootstrap.com/docs/5.3/components/navbar/) was taken from Bootstrap v5.3 documentation snippets.
* The carousel containing cards used on the menu.html page was inspired by a tutorial by [Coding Yaar](https://codingyaar.com/bootstrap-4-carousel-multiple-items-responsive/)
* The HTML for the [two carousels](https://getbootstrap.com/docs/5.3/components/carousel/) on the menu.html page, as well as the [cards](https://getbootstrap.com/docs/5.3/components/card/) used within these carousels, was taken from Bootstrap v5.3 documentation snippets.

### Content

Content for the website was written by Martyna Nowak.

## Bugs

### Solved bugs
* #### Footer
On the pages containing a smaller amount of content, such as index.html and contact.html, the footer was positioned halfway up the page instead of at the bottom. I tried various solutions, such as adding a sticky-bottom class or position: absolute or setting the bottom margin to 0; none of them worked appropriately. While position: fixed achieved the goal of keeping the footer at the bottom on all the pages, it caused the footer to obscure content on some pages. I created id 'fixed-footer' to apply position:fixed property only to pages with a small amount of content. However, some elements were still obscured while viewing the page on mobile. My final solution was to use media query and apply position:fixed to id 'fixed-footer' only for medium- and large-sized devices. According to manual testing carried on using Google Developer Tools, the solution worked and the footer remains at the bottom of all the pages on all devices without obscuring any content.
* #### Horizontal Overflow
A horizontal scrollbar kept appearing while viewing the website on mobile. As recommended to me on slack, I used Unicorn Revealer Chrome Extension to try and find out which element causes the overflowing, but to no avail. Finally, I followed an instruction from https://www.smashingmagazine.com/ and added a JavaScript snippet to the browser console. This showed that the culprit was a 'row' element within the footer. The overflow was fixed by adding 'm-0' class to the element.

![the javascript snippet used](docs/features/bug1.png)

* #### Contact Info Overlap
One of my peers on Slack pointed out that the contact information on the Contact Us page was overlapping when viewed on certain screen sizes. This was fixed by setting the 'overflow-wrap' property to 'break-word'. While this is not the optimal solution, as words breaking at random points can create a bad user experience, it was the only solution I found that stopped the content from overlapping. On most of the devices avaliable on Google Developer Tools, however, the text is aligned correctly without breaking mid-word. Perhaps future updates can implement a solution that keeps the contact info formatted properly on all screen sizes.

Before:

![before](docs/features/bug2.png)

After:

![after](docs/features/bug3.png)


## Deployment

1. Open the Github repository at [https://github.com/mmnowak/zesthouse](https://github.com/mmnowak/zesthouse)
2. Click on the Settings button;
3. Select Pages;
4. Select Source: Deploy from a branch and Branch: main / root;
5. Click Save and find your deployed website at an address shown on top of the page.

### Local Development

#### How to Fork

1. Open the Github repository at [https://github.com/mmnowak/zesthouse](https://github.com/mmnowak/zesthouse)
2. Click on the fork button found in the top right corner.

#### How to Clone

1. Open the Github repository at [https://github.com/mmnowak/zesthouse](https://github.com/mmnowak/zesthouse)
2. Click on the Code button;
3. Choose to clone using either HTTPS, SSH, or Github CLI and click the copy button to copy the link address;
4. In a code editor, change the current working directory to the location desired for the cloned directory;
5. Type 'git clone' into the terminal and paste the link address copied earlier;
6. Press enter to create a local clone.
  
##  Acknowledgments

I would like to express my gratitude to:
* My mentor, Mo Shami, for his guidance, support and advice;
* My peers and alumni on the Code Institute Slack who took the time to review my page and provide their feedback.

