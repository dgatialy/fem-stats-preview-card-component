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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- [CSS Variablen vs. SASS Variablen](https://codyhouse.co/blog/post/css-custom-properties-vs-sass-variables). CSS Variablen lassen sich irgendwie einfacher über mehrere Dateien hinweg verwenden. Bei SASS Vars. müssen diese immer erst import werden. Erscheint mir dann überflüssig. Dass man mit CSS Vars wohl flexibler ist und diese einfacher überschreiben kann
- SASS Dateistruktur 5-1 vs. 7-1 usw. Was gehört in "Abstracts" und was in "Base" noch keine Strategie.
- SASS Partials, @use und @forward
- REM vs. EM: [Use `rem` for Global Sizing; Use `em` for Local Sizing](https://css-tricks.com/rem-global-em-local/)
- Summary: em units for the font-size property will be relative to the font-size of the parent element. em units on other properties than font-size will be relative to the font-size of the current element. rem units sizes will always be relative to the font-size of the root html element. r = root (Merkhilfe) [Quelle](https://www.digitalocean.com/community/tutorials/css-rem-vs-em-units)
- https://piccalil.li/tutorial/fluid-typography-with-css-clamp/
- em shines when the behavior of spacing relative to the element is the desired effect. [Quelle](https://moderncss.dev/generating-font-size-css-rules-and-creating-a-fluid-type-scale/)
  To see how you can add code snippets, see below:
- Best practices für den Umgang mit Bildern. [Performance vs. Design](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/)
- [Fluid Type & Space](https://www.smashingmagazine.com/2021/04/designing-developing-fluid-type-space-scales/)
- Nächstes Projekt: erst Fluid Type & Space definieren. Spacings als Komponenten in Figma anlegen. Damit Designs erstellen. Dann grobe Struktur (rudimentäre Klassen vs. BEM) in HTMl erstellen und progressiv verbessern.
- Responsive Images und [Art Direction](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/#art-direction-can-do-a-lot-more-than-just-cropping)

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log('🎉');
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
