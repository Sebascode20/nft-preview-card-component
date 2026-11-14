# Frontend Mentor - NFT Preview Card Component

This is my solution to the [NFT Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

The project consists of a responsive NFT preview card that displays information about a digital collectible called **Equilibrium #3429**, including its description, Ethereum price, remaining time, and creator information.

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

- View the NFT preview card with an optimal layout.
- See hover states for interactive elements.
- View the NFT image overlay when hovering over the main image.
- See the NFT title and creator name change color on hover.
- Access the project on different screen sizes.

### Screenshot

![NFT Preview Card Component](https://previewcomponentcardnft.netlify.app/images/NFT-preview-card-component.png)

### Links

- Solution URL: [Sebascode20](https://github.com/Sebascode20/nft-preview-card-component)
- Live Site URL: [NFT Preview Card Component](https://previewcomponentcardnft.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3
- CSS pseudo-elements (`::before`)
- CSS pseudo-classes (`:hover`)
- CSS positioning (`relative`, `absolute`, `fixed`)
- CSS Flexbox concepts and inline elements
- Responsive image properties
- HSL color values
- Google Fonts - Outfit

### What I learned

During this project, I improved my understanding of semantic HTML5 and CSS styling techniques.

Some of the main concepts I practiced were:

**1. Semantic HTML5**

I used semantic elements such as `main`, `article`, `header`, and `footer` to organize the page structure and improve its readability.

**2. CSS pseudo-classes and pseudo-elements**

I learned how to use `:hover` to create interactive visual effects when users hover over specific elements.

I also practiced using the `::before` pseudo-element to create a colored overlay over the NFT image.

```css
header::before {
  background-color: hsl(178, 100%, 50%);
  position: absolute;
  content: "";
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  opacity: 0;
  cursor: pointer;
}

header:hover::before {
  opacity: 0.6;
  border-radius: 10px;
}
```

**3. CSS positioning**

I practiced using different positioning properties, including `relative`, `absolute`, and `fixed`, to position elements within the card and the attribution section.

**4. CSS selectors**

I improved my knowledge of class selectors, descendant selectors, adjacent sibling selectors, and pseudo-classes to apply styles to specific elements.

**5. Image styling**

I practiced using properties such as `max-width`, `height`, `object-fit`, and `border-radius` to control image dimensions and appearance.

## Continued development

In future projects, I want to continue improving my CSS skills, especially in the following areas:

- CSS Flexbox and Grid for more advanced layouts.
- Responsive web design using media queries.
- Advanced CSS selectors and pseudo-elements.
- CSS animations and transitions.
- Accessibility and semantic HTML best practices.
- Improving the organization and maintainability of CSS code.

## Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/) - A platform that provides practical frontend development challenges.
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Documentation for learning and improving HTML skills.
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - A useful resource for understanding CSS properties, selectors, and styling techniques.
- [CSS Tricks](https://css-tricks.com/) - Helpful guides and articles about CSS layouts and techniques.
- [The Markdown Guide](https://www.markdownguide.org/) - Documentation for writing and formatting Markdown files.

## Author

- GitHub: [@Sebascode20](https://github.com/Sebascode20)
- Frontend Mentor: [My Frontend Mentor Profile](https://www.frontendmentor.io/)

---

**Developed by Sebastian**