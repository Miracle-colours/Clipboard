# Frontend Mentor - Clipboard landing page solution

This is my solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9).

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Clipboard landing page screenshot](./screenshot.jpg)

### Links

- Solution URL: https://github.com/Miracle-colours/Clipboard
- Live Site URL: https://clipboard-two-nu.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS nesting
- Responsive design
- Media queries
- Google Fonts

### What I learned

This project helped me understand how to structure a webpage using semantic HTML and how to organize my CSS using nesting.

I practiced using Flexbox and CSS Grid to create layouts and make them responsive across different screen sizes.

I also learned more about CSS selectors and how nested selectors work.

For example:

```css
.features {
  display: flex;

  > div {
    flex: 1;

    img {
      max-width: 30rem;
    }
  }
}
```

### Continued development

I want to continue improving my understanding of:

-Responsive layouts
-Flexbox
-CSS Grid
-CSS nesting
-Media queries
-Writing cleaner CSS
-Building layouts without relying too much on trial and error.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - Used as a reference while learning and checking HTML and CSS concepts.

### AI Collaboration

I used AI tools during this project as a learning and debugging aid.

I used ChatGPT to help me understand CSS concepts ie nesting, Grid, and media queries.

I used Claude to help debug a deployment issue with Vercel. The problem turned out to be my project folder structure: my website files were nested inside another folder, so Vercel could not find the index.html file from the expected root directory.

## Author

- Frontend Mentor - [@Miracle-colours](https://www.frontendmentor.io/profile/Miracle-colours)
- Twitter - [@quiet_coder19](https://twitter.com/quiet_coder19)

## Acknowledgments

Thanks to my friend Femi for helping me debug the initial CSS loading issue when my browser could not find the resource.

T```

```

```
