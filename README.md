# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Basic HTML/CSS layout for a QR Code example card taken from www.frontendmentor.io

### Screenshot

![QR CODE TEST DESKTOP](./images/QR-CODE-TEST-DESKTOP.png)
![QR CODE TEST MOBILE](./images/QR-CODE-TEST-MOBILE.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Started with the HTML file, defined a .qr-component-container, .qr-component-main, .qr-component-text to have general container for all the elements inside, a div for the image, and a div for the text.
- I normalized some element of the style that I needed such as setting margin and padding both at 0, and setting the border-box. I also set the personalized color as per style-guide.
- After having styled the body so that the card was centered in the viewport, I procedeed by designing the size of the card container, the img inside and the text. Personally I chose to set a black solid border for everything in order to understand how much space each element was taking. I preferred to use flexbox as a main display for everything as it seemed the best solution to what I was aiming for.
- Lastly I just added the final decorations, such as deleting the borders I used to help myself, setting a box shadow, defining the font color.
- Personally I didn't use any media queries as the clamp attribute was already giving me enough responsiveness both in the desktop version and in the mobile version.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use the clamp attribute both in the container and in the image to better improve the responsiveness of those two elements. Now they re-size themselves well regardless the size of the viewport.

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=U9VF-4euyRo) - This helped me for the clamp and min/max/fit content values.

## Author

- Frontend Mentor - [@Molisana95](https://www.frontendmentor.io/profile/Molisana95)

