# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/Media/images/blog_card.png)

### Links

- Solution URL: [Blog Card](https://jardellprod.github.io/blog_card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how to use css box-shadow property. I also learned how to manipulate flexbox to vertically align an img and heading together. Lastly since the challenge provided an example of how the final product should look I tried using various plugins to determine the overall ratio of each component of the card.

```css
//using Flexbox for the author info
.card .card-info .card-author {
  display: flex;
  justify-content: flex-start;
}
```

```css
//aligning the text with the image
.card .card-info .card-author p {
  align-self: center;
  font-weight: bold;
}
```

### Continued development

I want to be better at using sementic html, I think there is some room for improvement to help improve search engines, and help improve the WCAG ratings. Also with more practice my css code can be more consised and cleaner.

## Author

- Website - [noobslice.com](https://www.noobslice.com)
- Frontend Mentor - [@jardellprod](https://www.frontendmentor.io/profile/jardellprod)

## Acknowledgments

Another great challenge from Frontend Mentor. I had a lot of fun completing it.
