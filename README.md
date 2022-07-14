# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [https://github.com/omerome83/Single-Price-Grid-Component](https://github.com/omerome83/Single-Price-Grid-Component)
- Live Site URL: [https://omerome83.github.io/Single-Price-Grid-Component](https://omerome83.github.io/Single-Price-Grid-Component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

After doing this challenge, I feel that I am a little more comfortable with CSS Grid. Work in progress! I was able to implement grid areas on both the desktop and the mobile version of the page which honestly, makes coding a mobile first page much easier. I also tried my hand at utilizing CSS variables which also makes life easier when I need to adjust a specific color. I can make the change in one place instead of finding it in each particular element.

Here is what I did when it came to defining each of the colors I wanted. This is SO much easier than adding them manually!

```css
:root {
  --primary-cyan: hsl(179, 62%, 43%);
  --primary-lighter-cyan: hsl(179, 62%, 45%);
  --primary-bright-yellow: hsl(71, 73%, 54%);
  --primary-bright-yellow-hover: hsl(71, 73%, 65%);

  --neutral-light-gray: hsl(204, 43%, 93%);
  --neutral-grayish-blue: hsl(218, 22%, 67%);
  --neutral-darker-shade-gray: hsla(0, 0%, 100%, 0.8);
  --neutral-background-gray: hsl(206, 47%, 93%);
  --neutral-white: hsl(0, 0%, 100%);
}
```

### Continued development

I hope to continue to become more comfortable with CSS Grid and the different ways I can implement it with more challenging designs. I also really want to start learning Javascript as I have trying to grasp the fundamentals. Now I just need a project to test my knowledge.

### Useful resources

- [Stackoverflow](https://stackoverflow.com/questions/13938975/how-to-remove-indentation-from-an-unordered-list-item) - Good source to help remove indentation when you want to list content neatly - without any bullets or numeration.


## Author

- Website - [Romel Williams](https://github.com/omerome83)
- Frontend Mentor - [@omerome83](https://www.frontendmentor.io/profile/omerome83)