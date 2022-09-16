# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
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

![](/design/stats-card-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://colinmcarthur85.github.io/stats-preview-card-component/)
- Live Site URL: [Add live site URL here](https://colinmcarthur85.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Custom Properies
- BEM Naming System
- Flexbox
- First time using :not pseudo element

### What I learned

SASS makes like MUCH easier. The nesting ALONE is worth the effort to learn it.

```css
// font-sizes
$fs-900: 3.75rem; // 60px
$fs-800: 3rem; // 48px
$fs-750: 2.5rem;
$fs-700: 2rem; // 48px
$fs-600: 1.5rem; // 24px
$fs-500: 1.3125rem; // 21px
$fs-400: 1.125rem; // 18px
$fs-300: 1rem; // 18px
```

```css
.card__content-stats .flex-col:not(:last-child) {
  margin-bottom: $size-32;
}
```

```css
.card {
  background-color: $clr-primary-400;
  color: $clr-neutral-700;
  max-width: 375px;
  margin-inline: auto;
  border-radius: 8px;
  overflow: hidden;

  &__image {
    width: 100%;
    opacity: 0.4;

    &-wrapper {
      margin-bottom: $size-8;
      background: $clr-primary-accent;
    }
  }

  etc
```

### Continued development

As clean as I feel my coding was I beleive that I can tidy it up better. I think Ill review the nesting portion of my SASS course from Kevin Powell one more time just to make sure Im clear on all things.
