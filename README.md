![Design preview for the NFT preview card component coding challenge](assets/design/desktop-preview.jpg)

# NFT preview card component solution

This project was developed from a [Frontend Mentor Challenge](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

The challenge is to build out this preview card component and get it looking as close to the design as possible.

This is a solution to the Frontend Mentor challenge help improve coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](assets\design\screenshot.png)

### Links

- Live Site URL: [NFT preview card component](https://filipesilvait.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned more about flexbox, I learned to separate content with the <hr> tag. I also learned how to style with border-shadow and use hover and an overlay image.

```css
.img-overlay {
    position: absolute;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    background-color: hsl(178, 100%, 50%, 0.5);
    display: none;
}
```
```css
.img-overlay img {
    position: absolute;
    width: 50px;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```

### Continued development

I will continue to learn more about semantic HTML5. Solidify, refine and learn more about flexbox, styles, positions and decorations.

## Author

- LinkedIn [Filipe Silva](https://www.linkedin.com/in/filipesilvait/)
- Twitter - [@filipesilvait](https://twitter.com/filipesilvait)
