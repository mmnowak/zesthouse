# ZestHouse Juice Bar

(Developer: Martyna Nowak)

The ZestHouse Juice Bar website is designed to be accessible and responsive on all devices. It allows easy access to a menu with prices, opening times, gallery, and information about the venue.

![an image of the webpage opened on different devices from amiresponsive](docs/features/amiresponsive.jpg)

Add a link to the live site here, for Milestone 1 this will be the GitHub Pages Link from when you deployed the site.

---

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
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
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#performing-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatibility)
    7. [Testing user stories](#testing-user-stories)
7. [Credits](#credits)
    1. [Media](#media)
    2. [Code used](#code-used)
8. [Bugs](#bugs)
9. [Deployment](#deployment)
11. [Acknowledgements](#acknowledgements)

## User Experience (UX)

### User Stories

**First Time Visitor Goals**

* I want to find out what ZestHouse is and what facilities are avaliable
* I want to find out where ZestHouse is
* I want to be able to navigate the website with ease

**Returning Visitor Goals**

* I want to be able to contact ZestHouse easily with any questions or feedback i might have
* I want to easly connect with their social media

## Design

### Colour Scheme
![The colour palette](docs/features//palette.png)

Two of the colours (#c92324 and #ea861a) used were chosen using a color picker from the background image(see the Imagery section below). Then a [colour palette generator](http://colormind.io/bootstrap/) was used to choose complimentary colours (#084208 and #f4f7f9). [The contrast checker](https://webaim.org/resources/contrastchecker/) showed that the contrast between the navbar background and text is good (ratio 10.88:1). However, the contrast ratio was too low for the colors used for the main paragraphs (#ea861a for the background and #084208 for the text). Thus, to improve accessibility, a lighter color (#f2d363) was choosen for the background, bringing the contrast ratio score to 7.96:1.


### Typography

The fonts used for the website are imported from [Google Fonts](https://fonts.google.com/).
The font chosen for the logo as well as all the headings is Viga. It is described as having a good performance on the screen as well as a great personality.

![A font sample](docs/features/fontviga.png)

A [font pairing website](http://www.ourownthing.co.uk/fontpairing/) was then used to pick Anek Bangla, the font used for all the other text, such as paragraphs and buttons.

![A font sample](docs/features/fontanek.png)

### Imagery

The image main image, used for the background, was chosen due to its vibrant colours and the fruit looking like its bursting with flavour and vitamins. It is supposed to be associated with concepts such as freshness, nutrition, health and wellness. 
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

<details><summary>Contact Us Page</summary>
<img src="docs/wireframes/mp1mobileform.png">
<img src="docs/wireframes/mp1deskopform.png">
</details>

## Features

### Logo and Navigation bar
* Featured on all pages, the navigation bar is fully responsive and changes to a burger toggler menu on smaller screens.
* The left of the navigation bar features a logo, which when clicked on leads to the index page. The right side contains links to the Home Page, About Us Page, Gallery, Menu Page and Contact Us Page.
* The link to the page the user is currently on is indicated by a different colour background.
* The Navigation bar was adapted from the code sourced from https://getbootstrap.com/docs/5.3/components/dropdowns/

### Footer
* Featured on all pages.
* Contains three sections: contact details, social media links and opening times.
* Social media links are represented by easily identified icons.

### Index Page
* Features a short text introducing the venue.
* Includes two call-to-action buttons, leading to the Menu page and About Us Page.

### About Us Page
* Includes a paragraph introducing the owners and the idea behind the business.
* Features description of facilities avaliable, accompanied by relevant pictures.
* Includes the venue location on an embeded Google Map.

### Gallery Page
* A masonry style picture gallery. Arranged in three columns on large- and medium-sized devices, and a single column on small screens.

### Menu Page
* Carousel

![Menu carousel on deskop](docs/features/menupagecarousel.jpg)
![Menu carousel on mobile](docs/features/menupagecarouselmobile.png)

If there is a feature that appears on all pages of your site, include it here. Examples of what to include would the the navigation, a footer and a favicon.

I then like to add a screenshot of each page of the site here, i use [amiresponsive](https://ui.dev/amiresponsive) which allows me to grab an image of the site as it would be displayed on mobile, tablet and desktop, this helps to show the responsiveness of the site.

### Future Implementations

What features would you like to implement in the future on your site? Would you like to add more pages, or create login functionality? Add these plans here.

### Accessibility

Be an amazing developer and get used to thinking about accessibility in all of your projects!

This is the place to make a note of anything you have done with accessibility in mind. Some examples include:

Have you used icons and added aria-labels to enable screen readers to understand these?
Have you ensured your site meets the minimum contrast requirements?
Have you chosen fonts that are dyslexia/accessible friendly?

Code Institute have an amazing channel for all things accessibility (a11y-accessibility) I would highly recommend joining this channel as it contains a wealth of information about accessibility and what we can do as developers to be more inclusive.

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

## Deployment & Local Development

👩🏻‍💻 View an example of a completed Deployment & Local Development section [here](https://github.com/kera-cudmore/TheQuizArms#Deployment)

### Deployment

Include instructions here on how to deploy your project. For your first project you will most likely be using GitHub Pages.

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

Place instructions on how to fork your project here.

#### How to Clone

Place instructions on how to clone your project here.

## Testing

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. No errors were found.

See scores:

[Index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io%2Findex.html)

[About.html](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io%2Fabout.html)

[Gallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io%2Fgallery.html)

[Menu.html](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io%2Fmenu.html)

[Contact.html](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io%2Fcontact.html)

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the css file for the website. No errors were found.
![CSS Validation score](docs/features/cssvalidation.png)

### Accessibility
The WAVE web accessibility evaluation tool by WebAIM was used to ensure the website is fully accessible.

See scores:

[Index.html](https://wave.webaim.org/report#/https://8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io/)

[About.html](https://wave.webaim.org/report#/https://8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io/about.html)

[Gallery.html](https://wave.webaim.org/report#/https://8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io/gallery.html)

[Menu.html](https://wave.webaim.org/report#/https://8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io/menu.html)

[Contact.html](https://wave.webaim.org/report#/https://8000-mmnowak-milestoneprojec-kvzu7gsosff.ws-eu97.gitpod.io/contact.html)

### Performance tests on various devices

The website was used on following devices:
* Thinkpad Yoga 460
* Xiaomi 11 Lite

As well as on all avaliable device options when using Google Chrome Developer tools.

### Browser compatibility

The website was tested on following browsers:

* Google Chrome
* Opera
* Microsoft Edge

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

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say? This is the best place to put this information.
  
##  Acknowledgments

If someone helped you out during your project, you can acknowledge them here! For example someone may have taken the time to help you on slack with a problem. Pop a little thank you here with a note of what they helped you with (I like to try and link back to their GitHub or Linked In account too). This is also a great place to thank your mentor and tutor support if you used them.

