# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.io/vibesprint/testimonial-grid](https://github.io/vibesprint/testimonial-grid)
- Live Site URL: [https://vibesprint.github.io/testimonial-grid](https://vibesprint.github.io/testimonial-grid)

## My process

### Built with

- Semantic HTML5 markup
- Sass CSS
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

Learned that CSS has its peculiarities. Like the rule that more specific rule applies if there's any collision between two. For example,
```css
article {
    margin: 0px;
}
// second rule

main article {
    margin: 0px;
}
```
Here the second rule will apply, even when it might have appeared before the first rule. It's because the second rule is more specific.

### Useful resources

- [https://cssreference.io/backgrounds/](https://cssreference.io/backgrounds/) - For background image property
- [https://www.w3schools.com/css/css_specificity_hierarchy.asp](https://www.w3schools.com/css/css_specificity_hierarchy.asp) - CSS specificity

### AI Collaboration

AI guided me towards the specificity rules and found the bug which was happening due to CSS specificity rules.

## Author

- Github - [https://github.com/vibesprint](https://github.com/vibesprint)
