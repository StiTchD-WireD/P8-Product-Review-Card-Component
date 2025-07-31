# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
Mobile:

![images/Screenshot Product preview card component Mobile.png](images/Screenshot%20Product%20preview%20card%20component%20Mobile.png)

Browser:

![images/Screenshot Product preview card component Browser.png](images/Screenshot%20Product%20preview%20card%20component%20Browser.png)

### Links

- Solution URL: [GitHub](https://github.com/StiTchD-WireD/P8-Product-Review-Card-Component)
- Live Site URL: [https://your-live-site-url.com](https://stitchd-wired.github.io/P8-Product-Review-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using different images depending on viewport

To see how you can add code snippets, see below:

```html
<div class="image">
  <picture>
    <source srcset="images/image-product-mobile.jpg" aria-describedby="perfume_name" media="(max-width: 672px)">
    <source srcset="images/image-product-desktop.jpg" aria-describedby="perfume_name" media="(max-width: 1500px)">
    <img src="images/image-product-mobile.jpg" alt="Bottle of Gabrielle Essence Eau De Parfum" aria-describedby="perfume_name">
  </picture>
</div>
```

### Continued development

Continue practice with clamp() min() max()

### Useful resources

- [https://www.w3schools.com/css/css_rwd_images.asp](https://www.example.com) - different images for different viewports.


## Author

- Frontend Mentor - [@StiTchD-WireD](https://www.frontendmentor.io/profile/yourusername)

