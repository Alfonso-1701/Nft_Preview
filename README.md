# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

Simple card that has 3 active states. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot](./images/screenshot.jpg)


### Links

- Solution URL: [https://github.com/Alfonso-1701/Nft_Preview](https://github.com/Alfonso-1701/Nft_Preview)
- Live Site URL: [https://fluffy-pixie-ef186a.netlify.app](https://fluffy-pixie-ef186a.netlify.app)

## My process

Started with mobile first. Set everything up and styled, then I went into set up active states before I addressed media queries. Got stuck on the viewing icon for the image. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I had some difficulty with the eye icon for the image. I rediscovered that positioning requires attention to the parent. The parent also needs to have relative positioning. The same is said for z-index. The z-index is relative to other elements, positioning AND placement. 

Discovered also that, obviously, you can not hover over something that isn't displayed. My first possible solution was trying to hide the image and when it was hovered over, it would become visible. 


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [https://developer.mozilla.org/en-US/docs/Web/CSS/z-index](https://developer.mozilla.org/en-US/docs/Web/CSS/z-index) - Helped me to clarify Z index and position. 

## Author

- Frontend Mentor - [@Alfonso-1701](https://www.frontendmentor.io/profile/Alfonso-1701)
- LinkedIn - [@Alfonso Alvarez](https://www.linkedin.com/in/alfonso-alvarez-4223b628b/)

