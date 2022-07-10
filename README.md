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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Just below , you can see something that i learned : How to make an Image Overlay ! Try It , it is really usefull !

```html
    <div class="hero-container">
      <img class="hero" src="./images/image-equilibrium.jpg" alt="Equilibrium">
        <div class="eye">
          <img src="./images/icon-view.svg" alt="An Eye">
        </div>
    </div>
```
```css
.hero {
    opacity: 1;
    display: block;
    width: 100%;
    height: auto;
    transition: .5s ease;
    backface-visibility: hidden;
    border-radius: 15px;
}

.eye {
    transition: .5s ease;
    opacity: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    text-align: center;
    padding: 42% 42%;
    border-radius: 15px;
    background-color:  hsla(178, 100%, 50%, 0.35);
}

.hero-container:hover .hero {
    opacity: 0.3;
}

.hero-container:hover .eye {
    opacity: 1;
    cursor: pointer;
}
```

### Useful resources

- [How to make an Image Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me to understand how to make an image overlay. I really liked this pattern and will use it going forward. Because , i had a hard hour, thinking about to really make it. The best choice was to google it ! I Made a snippet just above !

## Author

- Frontend Mentor - [@AklemX](https://www.frontendmentor.io/profile/ArklemX)

Thanks ! X)
