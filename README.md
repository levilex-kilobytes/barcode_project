# Frontend Mentor - QR Code Component Solution

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project helped me practice centering elements both vertically and horizontally using Flexbox. I also got more comfortable with the mobile-first approach using media queries.

Centering the card on the page:

```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
```

Using a clean card structure in HTML:

```html
<div class="card">
  <img src="/images/image-qr-code.png" alt="QR code" class="card__image" />
  <div class="card__body">
    <h1 class="card__title">
      Improve your front-end skills by building projects
    </h1>
    <p class="card__text">Scan the QR code to visit Frontend Mentor...</p>
  </div>
</div>
```

### Continued development

In future projects I want to focus on:

- Getting more comfortable with CSS Grid for complex layouts
- Learning how to build responsive layouts that shift between mobile and desktop
- Improving my eye for spacing and typography details

### Useful resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand how to center the card perfectly on the page.
- [MDN Web Docs - box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - Helped me fine-tune the card shadow.

## Author

- Frontend Mentor - levilexkilobytes(https://www.frontendmentor.io/profile/yourusername)
- Twitter - itzlevi005(https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io) for providing this challenge as a great starting point for beginners. Also a big thanks to Claude (Anthropic) for AI-assisted guidance throughout the build process.
