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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](./images/Frontend%20Mentor%20-%20QR%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://qr-component-raley17.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

The project was fast paced until I had to center the QR, so I spent more than an hour trying to figure out why the "body" was so small compared to other projects.
Then I realised that the body had no size min property.
Finally I came up with this:

body {
min-height: 100vh; <---------|
background-color: #d5e1ef;
font-family: "Outfit";
display: flex;
flex-direction: column;
}

### Continued development

I would like to improve my "muscle memory" writing code, meaning that I won't be commiting the type of mistakes I pointed in the section before.

### AI Collaboration

I used Claude AI when working on this project. Instead of just asking it to give me the solution, I asked what the problem was and which could be the ways of handling it.

## Author

- Frontend Mentor - [@Raley17](https://www.frontendmentor.io/profile/Raley17)
