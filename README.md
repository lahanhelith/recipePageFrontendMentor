# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Links

- Solution URL: [Solution URL](https://your-solution-url.com)
- Live Site URL: [Live Site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

I learned that most modern browsers do not render the borders of a <tr> element. So when you want to add borders dividers to the table except the last row you have to use it in this way.

```css
table, th, td{
    border-bottom: 1px solid hsl(24, 5%, 18%);
    border-collapse:collapse
}

table, tr:last-child td{
    border-bottom:none;
}
```

The first section of this code adds a bottom border and then sets the border-collapse property to collapse so that the borders of the <table>, <th>, and <td> elements merge into each other which looks as if there is only a single border. Then the second section of the code selects the bottom border of the <table>, and the <td> elements in the last <tr> element and removes the bottom border.

### Continued development

I have to refine my usage of css units since I still lack enough knowledge to use them properly.

## Author

- Frontend Mentor - [@lahanhelith](https://www.frontendmentor.io/profile/lahanhelith)

