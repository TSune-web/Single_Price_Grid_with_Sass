# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Single Price Grid with Sass.png](/images/Single_Price_Grid_with_Sass.png)


## My process

### Built with

- Semantic HTML5 markup
- SASS
- CSS custom properties
- Flexbox
- CSS Grid
- Box-shadow


### What I learned

### Nested rules of Sass
```scss
.parent-selector {
  color: papayawhip;

  .child-selector {
    color: black;
  }
}
```

### Box-shadow
- Reference taken from MDN Web Docs
```css
button {
  /* offset-x | offset-y | color */
  box-shadow: 60px -16px teal;

  /* or
  offset-x | offset-y | blur-radius | spread-radius | color */
  box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
}
```

### align-items - fill the width of screen
```css
.card {
  display: flex;
  align-items: stretch;
}
```


### Continued development

#### Styling with Sass
  - This was my first time to utilise a css framework apart from Bootstrap. I used sass variables, nested rules, and @import. There are so many more to explore about the language.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me for layout using grid and flexbox. I also used this website to learn about box-shadow.
- [Sass Documentation](https://sass-lang.com/documentation) - For this challenge, I referred to the introductory section for the basic application of sass. It has a lot more to offer.
