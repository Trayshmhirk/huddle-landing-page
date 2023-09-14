# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Huddle landing page with alternating feature blocks solution](#frontend-mentor---huddle-landing-page-with-alternating-feature-blocks-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screencapture-127-0-0-1-5500-index-html-2023-09-14-02_15_11.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/Trayshmhirk/huddle-landing-page)
- Live Site URL: [Add live site URL here](https://huddle-landingpage-frontend.netlify.app/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Open Sans Font](https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap) - For Fonts

### What I learned

```css
.foot-links a::after{
   content: '';
   position: absolute;
   bottom: 0;
   left: 0;
   right: 0;
   height: 2px;
   border-radius: 5px;
   background-color: var(--footer-txt-color);
   transform-origin: right;
   transform: scale(0);

   transition: transform 200ms ease-in;
}

.foot-links a:hover::after{
   transform: scale(1);
   transform-origin: left;
}
```


## Author

- Frontend Mentor - [@Trayshmhirk](https://www.frontendmentor.io/profile/Trayshmhirk)
- Twitter - [@TrayShmhirk01](https://www.twitter.com/TrayShmhirk01)
