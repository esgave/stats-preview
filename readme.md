# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- View the optimal layout for the component depending on their device's screen size

### Screenshot

![See screenshot](./screenshot1.png)
![See screenshot](./screenshot2.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Media queries

### What I learned

- I learned how to create image overlays in css. 
- I also learned how to display different images on different screen sizes using the HTML tag 'picture' 
- I gained hands-on experience with CSS Grid


```css
img {
    display: block;
    width: 100%;
    height: 100%;
    border-radius: 1.5rem 1.5rem 0 0;
}

.card-image {
    background-color: var(--SoftVioletOverlay);
    border-radius: 1.5rem 1.5rem 0 0;
}

.card-image img.overlay {
    mix-blend-mode: overlay;
}

```

```html
<picture>
    <source media="(min-width:768px)" srcset="/img/image-header-desktop.jpg">
    <img class="overlay" src="/img/image-header-mobile.jpg" alt="Header">
</picture>
```

### Useful resources

## Author

- Frontend Mentor - [@esgave](https://www.frontendmentor.io/profile/esgave)