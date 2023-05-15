# ZestHouse Juice Bar

(Developer: Martyna Nowak)

The ZestHouse Juice Bar website is designed to be accessible and responsive on all devices. It allows easy access to a menu with prices, opening times, gallery, and information about the venue.

Add an image of the finished site here. I like to use [amiresponsive](https://ui.dev/amiresponsive) to get an image of my site on all device sizes, and amiresponsive allows you to click links on the page and scroll, so each device can show a different element of your site.

Add a link to the live site here, for Milestone 1 this will be the GitHub Pages Link from when you deployed the site.

If you want to add optional [shields.io](https://shields.io) badges to your README, I like to add them to this section.

---

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

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

The main image, used for the background, is from [unsplash.com](https://unsplash.com/photos/drzu0uPgmoU). It is a royalty free image, and is credited to an user Engin Akyurt.

![halved oranges and pomagranates](docs/features/citrussmall.jpg)

The image was chosen due to its vibrant colours and the fruit looking like its bursting with flavour and vitamins. It is supposed to be associated with concepts such as freshness, nutrition, health and wellness. 

Images used for the facilities section in the About Us Page:

[Photo by Alexas Fotos on Pexels](https://www.pexels.com/photo/close-up-photo-of-stacked-tissue-rolls-10760874/)

[Photo by OVAN on Pexels](https://www.pexels.com/photo/person-sitting-facing-laptop-computer-with-sketch-pad-57690/)

[Photo by Ivan Samkov on Pexels](https://www.pexels.com/photo/people-celebrating-a-little-girl-s-birthday-7922014/)

Images used for carousel

[Photo by Louis Hansel on Unsplash](https://unsplash.com/photos/H7Lti8qa0dE?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
https://unsplash.com/photos/byzvm4J8Ljw

[Photo by Helena Yankovska on Unsplash](https://unsplash.com/photos/7EbGkOm8pWM)


Menu Images

Photo by Pranjall Kumar: https://www.pexels.com/photo/red-juice-in-glasses-8600079/
Photo by Studio Naae: https://www.pexels.com/photo/close-up-shot-of-a-glass-of-fruit-juice-13546345/
Photo by <a href="https://unsplash.com/@cravethebenefits?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Brenda Godinez</a> on <a href="https://unsplash.com/s/photos/smoothie?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  Photo by <a href="https://unsplash.com/it/@vickyng?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Vicky Ng</a> on <a href="https://unsplash.com/s/photos/smoothie-bowl?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  Photo by <a href="https://unsplash.com/@heftiba?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Toa Heftiba</a> on <a href="https://unsplash.com/s/photos/juice-shots?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  Photo by Mwabonje: https://www.pexels.com/photo/close-up-photo-of-latte-art-1714950/
  Photo by The Castlebar: https://www.pexels.com/photo/close-up-shot-of-glasses-of-cocktails-9201052/
  Photo by Roberto Shumski: https://www.pexels.com/photo/snack-foods-on-round-wooden-tray-9134584/
  Photo by <a href="https://unsplash.com/@sugercoatit?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Melissa Walker Horn</a> on <a href="https://unsplash.com/photos/ptvKywiTghw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
  
GALLERY IMAGES
https://unsplash.com/photos/t7wg7BJU2-s
Photo by Brooke Lark on Unsplash

https://unsplash.com/photos/CiDpRQ9oPso
Photo by Farhad Ibrahimzade on Unsplash
https://unsplash.com/photos/TgQkxQc-t_U
Photo by Whitney Wright on Unsplash
https://unsplash.com/photos/BT2hIfR5oj8
Photo by Louis Hansel on Unsplash
https://unsplash.com/photos/22fsBrruHPQ
Photo by Marc Babin on Unsplash
https://unsplash.com/photos/S3E8Y_SRPUw
Photo by Louis Hansel on Unsplash


### Wireframes

Wireframes were created for mobile and desktop using Balsamiq software.

#### Index Page
![Wireframe](docs/wireframes/mp1mobilehero.png)
![Wireframe](docs/wireframes/mp1deskophero.png)

#### About Us Page
![Wireframe](docs/wireframes/mp1mobilecarusel.png)
![Wireframe](docs/wireframes/mp1deskopcarusel.png)

#### Contact Us Page
![Wireframe](docs/wireframes/mp1mobileform.png)
![Wireframe](docs/wireframes/mp1deskopform.png)

## Features

👩🏻‍💻 View an example of a completed user experience section [here](https://github.com/kera-cudmore/TheQuizArms#Features)

This section can be used to explain what pages your site is made up of.

### General features on each page

##### Logo and Navigation bar
* Featured on all pages, the navigation bar is fully responsive and changes to a burger toggler menu on smaller screens.
* The left of the navigation bar features a logo, which when clicked on leads to the index page. The right side contains links to the Home Page, About Us Page, Gallery, Menu Page and Contact Us Page.
* The link to the page the user is currently on is indicated by a different colour background.
* The Navigation bar was adapted from the code sourced from https://getbootstrap.com/docs/5.3/components/dropdowns/

##### Footer
* Featured on all pages.
* Contains three sections: contact details, social media links and opening times.
* Social media links are represented by easily identified icons.

##### Index Page
* Features a short text introducing the venue.
* Includes two call-to-action buttons, leading to the Menu page and About Us Page.

##### About Us Page
* Includes a paragraph introducing the owners and the idea behind the business.
* Features description of facilities avaliable, accompanied by relevant pictures.
* Includes the venue location on an embeded Google Map.

##### Gallery Page
* A masonry style picture gallery. Arranged in three columns on large- and medium-sized devices, and a single column on small screens.

##### Menu Page

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

👩🏻‍💻 View an example of a completed Technologies Used section [here](https://github.com/kera-cudmore/Bully-Book-Club#Technologies-Used)

### Languages Used

Make a note here of all the languages used in creating your project. For the first project this will most likely just be HTML & CSS.

### Frameworks, Libraries & Programs Used

* Bootstrap
* Balsamiq
* Google Fonts
* Colormind.io
* Webaim.org Contrast Checker
* Hover.css by Ian Lunn
* FontAwesome


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

Start as you mean to go on - and get used to writing a TESTING.md file from the very first project!

Testing requirements aren't massive for your first project, however if you start using a TESTING.md file from your first project you will thank yourself later when completing your later projects, which will contain much more information.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

## Credits

Menu Carousel inspired by this tutorial https://codingyaar.com/bootstrap-4-carousel-multiple-items-responsive/

👩🏻‍💻 View an example of a completed Credits section [here](https://github.com/kera-cudmore/BookWorm#Credits)

The Credits section is where you can credit all the people and sources you used throughout your project.

### Code Used

If you have used some code in your project that you didn't write, this is the place to make note of it. Credit the author of the code and if possible a link to where you found the code. You could also add in a brief description of what the code does, or what you are using it for here.

### Content

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say? This is the best place to put this information.

###  Media

If you have used any media on your site (images, audio, video etc) you can credit them here. I like to link back to the source where I found the media, and include where on the site the image is used.
  
###  Acknowledgments

If someone helped you out during your project, you can acknowledge them here! For example someone may have taken the time to help you on slack with a problem. Pop a little thank you here with a note of what they helped you with (I like to try and link back to their GitHub or Linked In account too). This is also a great place to thank your mentor and tutor support if you used them.