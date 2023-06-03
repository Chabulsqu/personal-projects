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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![NFT Card Screenshot](./screenshot.jpg)

### Links

- Live Site URL: [https://chabulsqu.github.io/personal_projects/nft_preview/nft.html](https://chabulsqu.github.io/personal_projects/nft_preview/nft.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties and transitions
- Flexbox
- Mobile-first workflow

### What I learned

I learned to use transitions and variables a while ago and I was happy to be able to implement them, I also used ARIA roles for better web accessibility and added keyboard navigation.

```html 
<h1 tabindex="0">Equilibrium #3429</h1>
<div role="presentation"></div> <!-- Doesn't hide the content but the semantic meaning of the elmeent -->
```
```css
.h1:hover, h1:focus {
  color: var(--main-accent-color);
}
```

### Continued development

- Responsive Design in more screen sizes
- CSS transform and image scalling

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - This helped me with the syntax for focus and it refreshed my knowledge on flexbox.

## Author

- Github - [Chabulsqu](https://github.com/Chabulsqu)
- Frontend Mentor - [@Chabulsqu](https://www.frontendmentor.io/profile/Chabulsqu)
- Twitter - [@mateo_fain](https://www.twitter.com/mateo_fain)