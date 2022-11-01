# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: https://www.frontendmentor.io/solutions/nft-preview-card-just-on-html-and-css-MynVh2szuI
- Live Site URL: https://guidoghg.github.io/NFT-practice/

### Built with

- Visual Studio Code
- FlexBox

### What I learned

   What I learned was using CSS3 to make the main style of the page for some people may be easy but for me was challenging to 
   be able to come up with code only from my notes and my research to do what was requested.

.nftImage .hiddenImg {
    position:absolute;
    display:none;
}

.nftImage:hover .hiddenImg{
    display:flex;
    cursor: pointer;
}

.overlay {
    width: 17rem;
    height: 17rem;
    border-radius: 1rem;
    visibility: hidden;
    position: absolute;
    background-color: var(--cyan);
    opacity: .5;
}

.nftImage:hover .overlay {
    visibility: visible;
    cursor: pointer;
}
 
 I'm very proud of this snippet because it's was very hard for me, atleast, to come up with that and be sure that it works in every device.

### Useful resources

- [Example resource 1] blackbox.io/search - This helped me for getting some code snippets.

## Author

- Website - [Guido Guasch](https://github.com/guidoghg)
- Frontend Mentor - [@guidoghg](https://www.frontendmentor.io/profile/guidoghg)
