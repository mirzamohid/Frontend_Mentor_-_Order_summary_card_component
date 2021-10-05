# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover states for interactive elements

### Screenshot

*Mobile Version: 375px*
![Screenshot of Order Summary Card Component for mobile](./screenshots/Skrinsyot%202021-10-05%20pada%2008.59.39.png)

*Desktop Version: 1440px*
![Screenshot of Order Summary Card Component for desktop](./screenshots/Skrinsyot%202021-10-05%20pada%2009.00.56.png)

### Links

- Solution URL: [GitHub](https://github.com/mirzamohid/Frontend_Mentor_-_Order_summary_card_component)
- Live Site URL: [GitHub Pages](https://mirzamohid.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

1. To specify the position of the content, position property can be applied to a wrapper with several other properties as below:

```html
<div class="wrapper">
      <div class="card">
```
```css
.wrapper {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%)
}
```

2. CSS Bestfriend:

```css
*,
::before,
::after {
  margin: 0;
  box-sizing: border-box;
}
html,
body {
  margin: 0;
  padding: 0;
  min-height: 100%;
  font: font
```

### Continued development

I'm still not comfortable with CSS positioning (even though it is an easy topic). I also want to improve the understanding of how to handle flexbox property with other layout method.

### Useful resources

- [CSS Flex](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This article provides a simple explanation about Flexbox.

## Author

- Frontend Mentor - [@mirzamohid](https://www.frontendmentor.io/profile/mirzamohid)