# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Github](https://github.com/laravue-18/frontend-mentor-product-preview-card)
- Live Site URL: [Vercel](https://frontend-mentor-product-preview-card-one.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- TailwindCSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned


```html
<picture>
  <source media="(max-width: 639px)" srcset="./images/image-product-mobile.jpg" alt="Perfume Image"/>
  <source media="(min-width: 640px)" srcset="./images/image-product-desktop.jpg" alt="Perfume Image" />
  <img src="./images/image-product-mobile.jpg" alt="Perfume Image" />
</picture>
```