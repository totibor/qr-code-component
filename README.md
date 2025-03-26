# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)

## Overview

### Screenshot

<img src="result.png" width=400>

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Good to remember shorthand for the adding property:
```css
  /* padding: top | left and right | bottom */
  padding: var(--spacing-200) var(--spacing-200) var(--spacing-500);
```
How to change the behaviour of the `width` and `height` properties:
```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

### Continued development

I would like to automatically change the image (inner) border radius depending on the card (outter) border radius. There is a solution that I know of: `inner-radius = outter-radius - padding-between-elements` but in this case with `20px` outter-radius and `16px` padding does not give good looking result.
Probably a good problem to investigate CSS `min()`, `max()`, `clamp()` functions in the future.