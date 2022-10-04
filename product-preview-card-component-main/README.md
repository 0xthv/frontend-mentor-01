# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- [My solution](https://polite-medovik-b9dfb8.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Pseudo Elements

### What I learned

How to create the rounded photo + border

```css
.card-photo {
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translate(-50%, 50%);
  border-radius: 50%;
  background: var(--white);
  width: 7rem;
  height: 7rem;
  border: 0.375rem solid var(--white);
}
```

### Useful resources

https://stackoverflow.com/questions/15664706/using-margin-padding-to-space-span-from-the-rest-of-the-p

- [Rotate image](https://stackoverflow.com/questions/5087420/how-to-rotate-the-background-image-in-the-container) -
- [text-rendering: optimizeLegibility;](https://dev.to/mustapha/5-webdev-tips-you-may-want-to-know-2-41e) -
- [Background image](https://www.sitepoint.com/css3-transform-background-image/) -
- [Span block](https://stackoverflow.com/questions/15664706/using-margin-padding-to-space-span-from-the-rest-of-the-p)

## Author

- Frontend Mentor - [@0xthv](https://www.frontendmentor.io/profile/0xthv)
