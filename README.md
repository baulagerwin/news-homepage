# News Homepage

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

This news homepage will be an excellent opportunity to practice your CSS Grid skills. There will be lots of tricky decisions to make and plenty of learning opportunities!

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![News Homepage](./screenshot.webp)

### Links

- Live Site URL: [Add live site URL here](https://news-homepage-fm-challenge.netlify.app/)

## My process

### Built with

- HTML5
- CSS3

### What I learned

- Semantic HTML
- Using compressed fonts such as WOFF and WOFF 2.0 to minimize FOUT or FOIT and maximize initial load speed.
- Art Direction

```html
<picture>
  <source
    media="(max-width: 425px)"
    srcset="./assets/images/image-web-3-mobile.jpg"
  />
  <source
    media="(min-width: 426px)"
    srcset="./assets/images/image-web-3-desktop.jpg"
  />
  <img
    class="header-img"
    src="./assets/images/image-web-3-desktop.jpg"
    alt="An Art for Web 3."
  />
</picture>
```

- Checkbox Trick

```css
#nav-menu-checkbox:checked ~ .nav-links {
  left: 35vw;
}
```

### Continued development

In the future projects, I want to create a website with mobile-first approach.

### Useful resources

- [Checkbox Trick](https://www.youtube.com/watch?v=xMTs8tAapnQ&t=582s&ab_channel=CalerEdwards) - This helped me toggle the sidebar without the help of JavaScript

## Author

- Website - [Gerwin Baula](https://twelve-technologies.netlify.app/)

## Acknowledgments

I wanna thank fontsquirrel for free fonts [Check em out!](https://www.fontsquirrel.com/)
