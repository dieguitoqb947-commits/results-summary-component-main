# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Results Summary Component Screenshot](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/yourusername/results-summary-component)
- Live Site URL: [Live Demo](https://yourusername.github.io/results-summary-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox for layout
- Mobile-first workflow
- Google Fonts (Hanken Grotesk)
- Responsive design techniques

### What I learned

Through building this Results Summary Component, I strengthened my understanding of:

- **Responsive Design**: Creating layouts that adapt seamlessly from mobile to desktop using a mobile-first approach
- **CSS Custom Properties**: Using variables for colors and spacing to maintain consistency and enable easy theme modifications
- **Flexbox Layout**: Building flexible, maintainable layouts for component positioning and item alignment
- **Semantic HTML**: Using proper HTML structure to ensure accessibility and SEO
- **CSS Styling**: Creating visually appealing components with gradients, shadows, and hover effects

Key code snippet - CSS custom properties for color management:

```css
:root {
  --color-red: hsl(0, 100%, 67%);
  --color-yellow: hsl(39, 100%, 56%);
  --color-green: hsl(166, 100%, 37%);
  --color-blue: hsl(234, 85%, 45%);
}
```

HTML structure for dynamically populated list items:

```html
<li class="container__aside-item">
  <div class="item__order">
    <img src="./assets/images/icon-reaction.svg" />
    <p class="item__text">Reaction</p>
  </div>
  <span><strong>80</strong> / 100</span>
</li>
```

### Continued development

Future improvements for this project could include:

- **Animation Effects**: Implement smooth transitions and animations for score reveals on page load
- **Accessibility Enhancements**: Add ARIA labels and improve keyboard navigation support
- **Theme Variations**: Create different theme options (dark mode, high contrast) using CSS variables
- **Mobile Optimization**: Further refine the mobile experience and test on various devices
- **Performance**: Optimize images and minify CSS for faster load times

### Useful resources

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) - Essential reference for understanding flexbox layout techniques
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Comprehensive guide with visual examples
- [MDN - CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) - Documentation on CSS variables and custom properties
- [Google Fonts](https://fonts.google.com/) - For typography selection (Hanken Grotesk)
- [Frontend Mentor](https://www.frontendmentor.io/) - The source of this challenge and community feedback

## Author

- **Name**: Diego
- **Frontend Mentor**: [@yourusername](https://www.frontendmentor.io?ref=challenge)
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **Twitter**: [@yourusername](https://twitter.com/yourusername)
