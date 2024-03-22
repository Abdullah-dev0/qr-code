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

## Overview

Here you can see how my QR code component challenge looks like after finishing

### Screenshot

![My desktop design preview for the QR code component](./my-desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

First I edited HTML and add corresponding classes. After that I download font style and implement it inside HTML head. Same was for `style.css` after creating it. When setup was finished first I edit CSS with CSS reset and after that added styles that match design and given style guide. Hope you like it! 👋  

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Variables

### What I learned

This is first time I used CSS variables and I already like it and how many options can be adjusted using this feature!

First inside `:root` pseudo-class define variables like this:

```css
:root {
  --background: hsl(212, 45%, 89%);
  --hero-background: hsl(0, 0%, 100%);
  --fw-regular: 400;
  --fw-bold: 700;
  --fs-paragraph: 15px;
  --fc-header: hsl(218, 44%, 22%);
  --fc-paragraph: hsl(220, 15%, 55%);
}
```

and after defining just use them for style properties using `var(--name)` as property value

```css
.hero__title {
  color: var(--fc-header);
  font-weight: var(--fw-bold);
  font-size: 1.375rem;
  text-align: center;
  margin-bottom: 1rem;
}
```

### Continued development

After finishing this small challenge I will learn more about CSS and try to think in a more responsive development way

### Useful resources

- [Mozilla CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This documentation helped me for using CSS variables. I really liked this pattern and will use it going forward.
- [Joshua custom CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This is an amazing article which helped me finally understand how CSS reset works. I'd recommend it to anyone still learning this concept, and thanks Josh for sharing it whith us!

## Author

- Frontend Mentor - [@jmarsic](https://www.frontendmentor.io/profile/jmarsic)
