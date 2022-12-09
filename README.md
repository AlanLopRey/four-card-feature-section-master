# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

desktope
![desktop](./screenshots/Screenshot%202022-12-08%20at%2019-41-48%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

mobile
![mobile](./screenshots/Screenshot%202022-12-08%20at%2019-45-00%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [Solution URL here](https://github.com/AlanLopRey/four-card-feature-section-master)
- Live Site URL: [Live site URL here](https://alanloprey.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS pre-processor
- [BEM metodology](https://getbem.com/) - Block Element Modifier metodology

### What I learned

I put in practice the positioning with the use of the grid lines, beside that was pretty easy and I like doing this challenge, I also set all the card with a specific width and height

```css
.article {
  width: 22.1875rem;
  height: 15.625rem;
}
.calculator {
  grid-row: 2/4;
  grid-column: 3/4;
}
.karma {
  grid-row: 3/5;
  grid-column: 2/3;
}
.supervisor {
  grid-row: 2/4;
  grid-column: 1/2;
}
.team {
  grid-row: 1/3;
  grid-column: 2/3;
}
```

### Continued development

I felt like i could do a better job without the necessity of put margins and paddings in the cards as well as all the content, maybe I found out a better way in the future, also i think I need to study more CSS cuz I felt with certain lack of knowledge but well I do my best

### Useful resources

- [piccalil](https://piccalil.li/blog/a-modern-css-reset/) - This page helped me to get a better reset of my code

## Author

- Frontend Mentor - [@AlanLopRey](https://www.frontendmentor.io/profile/AlanLopRey)
