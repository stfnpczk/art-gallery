# Frontend Mentor - Art gallery website solution

This is a solution to the [Art gallery website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

<br>

![](./assets/preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each page depending on their device's screen size
- See hover states for all interactive elements throughout the site
- **Bonus**: Use [Leaflet JS](https://leafletjs.com/) to create an interactive location map with custom location pin

### Links

- [Frontend Mentor - solution URL](https://www.frontendmentor.io/solutions/twopage-art-gallery-website-using-scss-and-grid-uKxnRLxm5)
- [Live Demo](https://stfnpczk.github.io/art-gallery/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- CSS Grid
- Flexbox
- BEM methodology
- Mobile-first workflow

### What I learned

- In this challenge I learned more about using grid layout and making it responsive using vw units.

```scss
.grid-container {
  grid-template-columns: 30.903vw 11.111vw 30.903vw;
  grid-template-rows: 27.778vw 21.736vw 26.181vw;
}

.grid-item {
  grid-column: 1/3;
  grid-row: 2/4;
}
```

- `mix-blend-mode: difference` -> in the special case of black and white, difference generates the respective color opposites.  





### Useful resources

- [MDN -> CSS Grid Layout ](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) 
- [DEV.to post -> mix-blend-mode ](https://dev.to/wgao19/night-mode-with-mix-blend-mode-difference-23lm) 



## Author

- Frontend Mentor - [@stfnpczk](https://www.frontendmentor.io/profile/stfnpczk)

