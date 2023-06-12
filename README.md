# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

![](https://github.com/jose-jimmy/Images-in-readme/assets/88069006/cbcf4eac-7976-4882-b8a2-78829d99ba73)

![](https://github.com/jose-jimmy/Images-in-readme/assets/88069006/2ff47ff6-1eb8-42a5-a3de-3e2126eae93a)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use the adjacent sibling selector to make the view icon appear on hover.


```css
.view {
  display: none;
}
.image-container:hover .overlay + .view {
  display: block;
}
```


### Useful resources

- [How To Create an Overlay Image Icon](https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me to add an overlay to the image on hover.


## Author

- Frontend Mentor - [@josejimmy](https://www.frontendmentor.io/profile/jose-jimmy)
- Twitter - [@josejimmy8055](https://twitter.com/josejimmy8055)
- LinkedIn - [@josejimmy](https://www.linkedin.com/in/jose-jimmy//)



