# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot/screencapture-darling-paletas-2041be-netlify-app-2022-09-10-05_59_16.png)

### Links

- Solution URL: [Github](https://github.com/pippal5536/front-end-mentor-stats-preview-card-component-main)
- Live Site URL: [Netlify](https://darling-paletas-2041be.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

### What I learned

```
I learnt something really really interesting. I learnt about the isolation property and I used pseudo element ""after"" for the first time to blur color on image
.card-image {
  background-image: url("./images/image-header-mobile.jpg");
  height: 30%;
  background-repeat: no-repeat;
  background-size: contain;
  position: relative;
  isolation: isolate;
  max-width: 100%;
  background-position: center;
  border-radius: 0.9rem 0.9rem 0 0;
}
.card-image::after {
  content: "";
  inset: 0;
  position: absolute;
  background-color: rgba(157, 0, 255, 0.4);
  z-index: -1;
  border-radius: 0.9rem 0.9rem 0 0;
}
```

### Continued development

I need to work on flexbox, pseudo elements and box model

### Useful resources

- [Kevin Powell](https://www.youtube.com/watch?v=lRPguPbovro&list=PLcz6t4PTWh2X7RuAgkVH5TItg8qF9I_iJ&index=108) - With the help of Kevin's video, I made the color blur using "after" pseudo element.

## Author

- Frontend Mentor - [@pippal5536](https://www.frontendmentor.io/profile/pippal5536)
