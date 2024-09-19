# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/qr-code-scanner-with-css-styling-and-positioning-VfxAJIfmRf)
- Live Site URL: [makeitqr](https://makeitqr.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
What I learned in this challenge is the use of flexbox to center a div. For example, you have a main container who want to be appeared at the center of the page:

```html
  <div class="card">
    <img src="./images/image-qr-code.png" alt="QR code">
    <h1>Improve your front-end</br>skills by building projects</h1>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </p>
  </div>
```
we can do the following thing by making the parent element set the layout:
```css
body {
    background: hsl(212, 45%, 89%);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
```
Also, one thing strike for me is how to import [Google Fonts](https://fonts.google.com) in CSS. 
- Navigate to your fonts you want to use, for the challenge I used the [Outfit](https://fonts.google.com/specimen/Outfit) font.
- Get the @import url of your font and use it **font-family** attribute:
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');

.card h1 {
    font-weight: 700;
    font-family: "Outfit", sans-serif;
    color: hsl(218, 44%, 22%);
    margin-top: 20px;
    font-size: 26px;
}
```


### Continued development
This is a potential project in the near future wherein you can generate a QR Code based on the links provided in the input by user.
Perhaps, I can use some libraries existing to do that, and power-up with framework like ReactJS.

## Author

- Website - [keiru.vercel.app](https://keiru.vercel.app/)
- Frontend Mentor - [@Ashtreus1](https://www.frontendmentor.io/profile/Ashtreus1)
- Facebook - [Keiru](https://www.facebook.com/jameson.gelarman)


