# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshots/Desktop-view.png)
![](./screenshots/Tablet-view.png)
![](./screenshots/Mobile-view.png)

### Links

- Solution URL: [@Timbar09](https://github.com/Timbar09/Huddle-landing-page-with-single-intro-section.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use CSS variables within specific elements which redused repetition of the same code, and also writing less code in general.

Here is a snippet of how I learned how to use CSS variables to good effect.

```css
.hero__social a {
  --border: 1px;
  --dimension: 28px;
  --line-height: var(--dimension);

  display: inline-block;
  color: var(--white);
  font-size: 0.875rem;
  border: solid var(--border) var(--white);
  width: var(--dimension);
  height: var(--dimension);
  line-height: var(--line-height);
  border-radius: 50%;
  transition: border 200ms ease-in-out, color 200ms ease-in-out;
}
@media (min-width: 1020px) {
  .hero__social a {
    --border: 2px;
    --dimension: 40px;
    --line-height: 37px;

    font-size: 1.25rem;
    text-align: center;
  }
}
```

### Continued development

I want to continue to focus more on flexbox. I thought i had grasped it but while working on this challenge I realised that there still a lot I don't about flexbox.

## Author

- Website - [Miles Mosweu](https://www.my-site-still-under-construction.com)
- Frontend Mentor - [@Timbar09](https://www.frontendmentor.io/profile/Timbar09)

## Acknowledgments

Firstly I would like to thank myself for copmleting this challenge and I also want to thank Frontend Mentor for helping me and so many others by giving us access to these challenges and helping us develop our coding skills.
