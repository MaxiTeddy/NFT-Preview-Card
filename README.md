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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://lh5.googleusercontent.com/ruCOmuTI3w-osus9mlHvNDLLf7r2j8ZVBP1ukvj2yyoIlYiMMPwvIoLiex87o7b-csw=w2400)

### Links

- Solution URL: [Here is the code](https://github.com/MaxiTeddy/NFT-Preview-Card/)
- Live Site URL: [Here's the live site for the code](https://nft-card-mu.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

How to hover an image using an image

There's what the code looks like, see below:

```html
<div class="picture">
            <img src="/images/image-equilibrium.jpg" class="image" alt="A NFT Stone">
            <img src="/images/icon-view.svg" class="view" alt="View">
            </div>
```
```css
.image{
        width: 300px;
        opacity: 1;
        display: block;
        height: auto;
        transition: .5s ease;
        backface-visibility: hidden;
        border-radius: 10px;
    }
    
    .picture{
        width: 300px;
        position: relative;
        cursor: pointer;
    }
    
    .view{
        transition: .5s ease;
        opacity: 0;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
    }
    
    .picture:hover{
        background-color: hsl(178, 100%, 50%);
        border-radius: 10px;
    }
    
    .picture:hover .view {
        opacity: 1;
    }
    
    .picture:hover .image{
        opacity: 0.3;
    }
}
```

### Continued development

I would love to understand more about hovering and transform

### Useful resources

- [W3 School](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me with the hovering of the image


## Author

- Github - [@MaxiTeddy](https://github.com/MaxiTeddy)
- Frontend Mentor - [@MaxiTeddy](https://www.frontendmentor.io/profile/MaxiTeddy)
- Twitter - [@OgijiMax](https://www.twitter.com/OgijiMax)

## Acknowledgments

I would love to thank [@SaOgiji](https://github.com/SaOgiji) for his support, encouragement and guidance.
