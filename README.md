# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

(./screenshot.png)
(./screenshot1.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

To see how you can add code snippets, see below:

```html
<img class="PP" src="images/image-avatar.png" alt="PP" />Creation of ‎
<a href="index.html">Jules Wyvern</a>
```

```css
.card {
  position: relative;
  display: grid;
  width: 330px;
  border-radius: 10px;
  padding: 20px 20px 20px 20px;
  grid-template-rows: repeat(5, auto);
  grid-template-columns: 165px 165px;
  row-gap: 25px;
  grid-template-areas:
    "cube cube"
    "title title"
    "text text"
    "eth days"
    "name name";
  background-color: hsl(216, 50%, 16%);
  -webkit-box-shadow: 15px 17px 5px 0px rgba(0, 0, 0, 0.15);
  -moz-box-shadow: 15px 17px 5px 0px rgba(0, 0, 0, 0.15);
  box-shadow: 15px 17px 5px 0px rgba(0, 0, 0, 0.15);
}
```

### Useful resources

-[Google fonts](https://fonts.google.com/)

## Author

- Frontend Mentor - [@Zakinane](https://www.frontendmentor.io/profile/Zakinane)
- TGitHub - [Zakinane](https://github.com/Zakinane)
