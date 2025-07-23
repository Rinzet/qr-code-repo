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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Project Screenshot](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/Rinzet/qr-code-repo)
- Live Site URL: [Github Pages](rinzet.github.io/qr-code-repo/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS (modularized with partials and variables)
- CSS Flexbox
- Mobile-first workflow

### What I learned

This project helped reinforce the importance of clean and structured layout using **Flexbox** for vertical and horizontal alignment. It also gave me my first hands-on experience working with **SCSS**, where I used:

- Variables for color management
- Mixins for consistent typography
- File splitting with `@import` and partials

```scss
body {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background: $slate-300;
}
```

I also learned how to manage layout responsiveness using `max-width`, `fit-content`, and padding.

### Continued development

In future projects, I’d like to:
- Continue improving my SCSS structure by exploring `@use` and `@forward`
- Use CSS Grid more confidently
- Deepen my understanding of responsive design across multiple breakpoints

### Useful resources

- [Frontend Mentor Help Center](https://www.frontendmentor.io/resources) - For tips on setup and best practices
- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Always useful for layout clarification
- [Sass Documentation](https://sass-lang.com/documentation) - For understanding SCSS features and structure

## Author

- Frontend Mentor - [@Rinzet](https://www.frontendmentor.io/profile/Rinzet)

## Acknowledgments

Thanks to the Frontend Mentor community for inspiring solutions and feedback. Also, shoutout to the devs who share their project file structures online—it helped me understand SCSS architecture better.