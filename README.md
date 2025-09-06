# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

#### Mobile
![Mobile](./assets/mobile/mobile_screenshot.png)
#### Tablet
![Tablet](./assets/tablet/tablet_screenshot.png)
#### Desktop
![Desktop](./assets/desktop/desktop_screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

#### Use of Pseudo-elements

```css
.hero {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr;
    gap: var(--space-400);
}

.hero::before {
    content: '';
    display: inline-block;
    background: url(/assets/desktop/image-hero-left.png) top left/contain no-repeat;
}

.hero__cta {
    grid-column: 2;
    grid-row: 1;
}

.hero::after {
    content: '';
    display: inline-block;
    background: url(/assets/desktop/image-hero-right.png) top right/contain no-repeat;
}
```

## Author

- Frontend Mentor - [@ashkir004](https://www.frontendmentor.io/profile/ashkir004)



## Acknowledgments

- Frontend Mentor - [Frontendmentor.io](https://www.frontendmentor.io/)

- - Netlify - [Netlify.com](https://www.netlify.com/)

