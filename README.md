# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./screenshots/Screenshot%202025-02-19%20at%2014-19-53%20Frontend%20Mentor%20Recipe%20page.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/gabriel-de-azevedo/recipe-page-main)
- Live Site URL: [GitHub Page](https://gabriel-de-azevedo.github.io/recipe-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS utility classes
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I decided to go easy the Style Reset for this one and rely a little bit on some HTML defaults, mainly when it comes to the lists and the table in this design. I had to make a few more adjustments than I'd hoped, but they were fairly straightforward.

This is what the **list** styles look like:

```css
.recipe-card ul,
.recipe-card ol {
  padding-left: 1em;
}

.recipe-card li {
  padding-left: 1em;
}

.recipe-card li::marker {
  font-weight: bold;
  padding-left: 1em;
  color: var(--clr-brown-800);
}
```

Simple enough.

And here's the **table**:

```css
.recipe-card .nutrition-table {
  width: 100%;
}
.recipe-card .nutrition-table tr {
  display: flex;
  justify-content: space-between;
  padding: 1em;
}

.recipe-card .nutrition-table tr + tr {
  border-top: 1px solid var(--clr-stone-150);
}

.recipe-card .nutrition-table td {
  width: 50%;
  padding-left: 1.5em;
}

.recipe-card .nutrition-table td strong {
  color: var(--clr-brown-800);
}
```

The table took a little bit more work but it's still very easy to read.

Overall, I'm pretty happy with how semantic the HTML tags ended up and that I was able to stick pretty close to their default behavior.

## Author

- GitHub - [gabriel-de-azevedo](https://github.com/gabriel-de-azevedo)
- LinkedIn - [gabriel-marques-de-azevedo](https://www.linkedin.com/in/gabriel-marques-de-azevedo/)
- Frontend Mentor - [@gabriel-de-azevedo](https://www.frontendmentor.io/profile/gabriel-de-azevedo)
