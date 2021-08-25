# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- [Solution URL](https://github.com/dgatialy/fem-stats-preview-card-component)
- [Live Site URL](https://modest-joliot-17adc9.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox 
- Parcel
- Design Tokens
- Figma for Design
- Netlify

### What I learned

- [CSS variables vs. SASS variables](https://codyhouse.co/blog/post/css-custom-properties-vs-sass-variables). CSS variables are somehow easier to use across multiple files. With SASS variables, they always have to be imported first?! Seems superfluous to me then. That one is probably more flexible with CSS variables and can overwrite these more simply

- SASS Partials, @use und @forward
- REM vs. EM: [Use `rem` for Global Sizing; Use `em` for Local Sizing](https://css-tricks.com/rem-global-em-local/)
> em units for the font-size property will be relative to the font-size of the parent element. em units on other properties than font-size will be relative to the font-size of the current element. rem units sizes will always be relative to the font-size of the root html element. r = root (Merkhilfe) [digitalocean.com](https://www.digitalocean.com/community/tutorials/css-rem-vs-em-units)

> em shines when the behavior of spacing relative to the element is the desired effect. [moderncss.dev](https://moderncss.dev/generating-font-size-css-rules-and-creating-a-fluid-type-scale/)
  

### Continued development

- SASS file structure 5-1 vs. 7-1 etc. What belongs in "Abstracts" and what in "Base". Here I don't have a proper strategy yet.
- Next project: first try to define "Fluid Type & Space". Then create spacings as components in Figma. Create designs with them. Then create rough structure (rudimentary classes vs. BEM) in HTML and refactor..


### Useful resources

- [Fluid Type & Space](https://www.smashingmagazine.com/2021/04/designing-developing-fluid-type-space-scales/)
- [A Guide to the Responsive Images Syntax in HTML ](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/)
    - [Responsive Images and Art Direction](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/#art-direction-can-do-a-lot-more-than-just-cropping)
- [Fluid typography with CSS clamp](https://piccalil.li/tutorial/fluid-typography-with-css-clamp/)