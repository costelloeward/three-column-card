# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Solution URL: [https://github.com/costelloeward/three-column-card](https://github.com/costelloeward/three-column-card)
- Live Site URL: [https://costelloeward.github.io/three-column-card/](https://costelloeward.github.io/three-column-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Tried out CSS variables for the colours and font.
```css
:root {
  --background: hsl(0, 0%, 95%);
  --big-font: 'Big Shoulders Display', cursive;
  --focus:hsla(70, 85%, 60%);
  --moss: hsl(179, 100%, 13%);
  --teal: hsl(184, 100%, 22%);
  --para-color: hsl(0, 0%, 100%, 0.75);
  --orange: hsl(31, 77%, 52%);
  --small-font: 'Lexend Deca', sans-serif;
}
```


```css
.sedans button {
  color: var(--orange);
}
```


### Continued development

The design only specified hover states for the buttons, I added a focus state as well. There would also need to be an active state.

I pretended that the buttons opened forms. If they were links I would style them different. 

```html
<button aria-label="open sedan form">Learn More</button>
```

## Author

- Website - [Costelloeward Design](https://www.costelloeward.design)
- Frontend Mentor - [@louisecw](https://www.frontendmentor.io/profile/louisecw)
- Twitter - [@louise_c_w](https://www.twitter.com/louise_c_w)



