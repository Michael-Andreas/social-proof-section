# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./images/Screenshot%202026-03-03%20at%2021-43-02%20Frontend%20Mentor%20Social%20proof%20section.png)
- alt="Frontend Mentor Social proof section challenge solution showing a responsive layout with three stacked card columns displaying customer testimonials and star ratings. The design demonstrates a grid layout with offset vertical positioning creating a cascading visual effect. Desktop view of the completed project."

### Links

- Solution URL: [frontendmentor.io/solutions/social-proof-section-JmbYJ23hJv](https://www.frontendmentor.io/solutions/social-proof-section-JmbYJ23hJv)
- Live Site URL: [github.com/Michael-Andreas/social-proof-section](https://github.com/Michael-Andreas/social-proof-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
section {
  max-width: 69.375rem;
  padding-top: 64px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
}

article:nth-child(2) {
  transform: translateY(16px);
}

article:nth-child(3) {
  transform: translateY(32px);
}
```

## Author

- Website - [www.michaelandreas.de](https://www.michaelandreas.de)
- Frontend Mentor - [@Michael-Andreas](https://www.frontendmentor.io/profile/Michael-Andreas)
