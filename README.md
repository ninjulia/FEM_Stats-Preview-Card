# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

[screenshot](https://ninjulia.github.io/FEM_3-Col-Preview-Card/screenshot.png)

### Links

- Solution URL: [https://github.com/ninjulia/FEM_Stats-Preview-Card](https://github.com/ninjulia/FEM_Stats-Preview-Card)
- Live Site URL: [https://ninjulia.github.io/FEM_3-Col-Preview-Card](https://ninjulia.github.io/FEM_3-Col-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS variable properties
- Flexbox
- Mobile-first workflow

### What I learned

This was coded mobile-first and leverages Flexbox for the layout and used CSS Variables to handle the colors.  As this is a component card, I used H3 tags for the headlines. I could just as well have used H1 tags but felt the H3 was better for extensibility. I also named the different sections based on order so that they might be more reusable as well.  One issue I noticed with flexbox is that it will cause images and buttons to fill the width of their containers and found the solution is to add width:max-content;  

### Continued development

Naming things is hard.  So is keeping padding consistent between elements. In retrospect, I should have set up variables with padding to keep everything consistent. Also, I am not sure about the extensibilyt of using :root as a place to store variables for components.  Ideally, a card component would be part of a larger process coded in SASS, which also would have helped with the color-specific classes.  

## Author

- Website - [Julia](https://www.becausejulia.com)
- Frontend Mentor - [@ninjulia](https://www.frontendmentor.io/profile/ninjulia)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
