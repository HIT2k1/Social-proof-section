# Social-proof-section

![](./design/desktop-preview.jpg)

# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size


### Links

- Solution URL: https://github.com/HIT2k1/Social-proof-section
- Live Site URL: https://hit2k1.github.io/Social-proof-section/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

- When I use display:flex for the container, I can't set the margin-top for items as what I want. Therefore, I used transform: translateY() to solve that problem.
- To change the src attribute in HTML, I use content:url() in CSS following:
```html
<img src="./images/bg-pattern-top-desktop.svg" alt="" class="pattern-top">
```
```css
.pattern-top {
  content: url(./images/bg-pattern-top-mobile.svg);
}
```

### Useful resources

https://stackoverflow.com/questions/2182716/is-it-possible-to-set-the-equivalent-of-a-src-attribute-of-an-img-tag-in-css - This is an amazing article which helped me finally change the src attribute in HTML.

## Author

- Frontend Mentor - @HIT2k1
