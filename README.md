# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This challenge is all about writing semantic HTML. And, as always, keeping it responsive.

### Screenshot

[screenshot of Recipe Page](<Screenshot 2024-06-13 at 18-25-12 Frontend Mentor Recipe page.png>)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I actually built out the project originally in Sass, which allowed me to jump start the code with some reusable partials.
Then, before uploading I switched to vanilla CSS just so I could hurry up and finish.

I found this project very challenging, as the color palette was a strain on my eyes, and at first I had a hard time seeing what was going on. Once I started, I just guessed what it should look like, and I am satisified with the result. However, the strain it put on my eyes makes me wonder if this is something other seniors with poor eyesight would struggle with.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass / scss

### What I learned

Mostly this was a review of previously learned material. I learned about the ::marker element and how to style list markers.

First time using CSS nesting. I like it; it organizes grouped styles together (like the table styles below).

```css
/* table styles */
.Nutrition table {
  border-collapse: collapse;
  width: 100%;
  tr {
    border-bottom: 1px solid var(--light-grey);
  }
  tr:last-child {
    border: none;
  }
  td {
    padding-left: 10px;
  }
}
```

### Continued development

I don't like the desktop styles in the media query; it looks really messy. My goal was to keep it DRY (don't repeat yourself) with all the margin-bottoms and padding. Perhaps a better organized html would help, something more modular.

I will continue with Sass as I am really liking it. Next up is mixins and functions. I will also explore Bootstrap for protoyping in order to get off to a quicker start.

### Useful resources

- [Resource 1](https://www.youtube.com/watch?v=svhnI9sKUDI&t=335s) - This helped me to better understand how to style list markers. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)
