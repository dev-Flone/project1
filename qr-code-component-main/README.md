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
Desktop with 1440px width
![](.ss/desktop.png)
![](.ss/desktop-max-width.png)
Mobile
![](.ss/mobile.png)
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flexbox
- Mobile-first workflow

### What I learned

While working on this project, I practiced writing **semantic HTML** and applying **responsive constraints** for different screen sizes.

For example, I learned how to restrict the page width between **375px (mobile)** and **1440px (desktop)** while keeping the QR card centered:

```css
body {
  min-height: 100vh;
  min-width: 375px;
  max-width: 1440px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: hsl(212, 45%, 89%);
  font-family: "Outfit", sans-serif;
}
```
