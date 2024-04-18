# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots

![](./screenshot.jpg)
![](./screenshot_mobile.jpg)

### Links

- [Source code](https://github.com/theGamingKitten/product-preview-card-component-main)
- [Live Site](https://thegamingkitten.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/) - utility-first CSS framework

### What I learned

- Getting a lot more confident with using Tailwind. Only had to look up one very specific class (letter spacing => tracking) for the mobile view.

- How to use a different picture based on the screen size:
```html
<picture>
  <source srcset="./src/images/image-product-mobile.jpg">
  <source srcset="./src/images/image-product-desktop.jpg" media="(min-width: 768px)">
  <img class="max-w-full h-full rounded-t-lg md:rounded-tr-none md:rounded-t-lg md:rounded-bl-lg" src="./src/images/image-product-mobile.jpg" alt="hero image">
</picture>
```

### Continued development

- Using Tailwind from the start without using custom css classes first and translating to Tailwind later.

### Useful resources

- [Tailwind CSS docs](https://tailwindcss.com/) - Documentation for Tailwind CSS

## Author

- Frontend Mentor - [@theGamingKitten](https://www.frontendmentor.io/profile/theGamingKitten)