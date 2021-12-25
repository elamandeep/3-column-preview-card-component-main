# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./desktop.jpg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
This challenge was interseting . Earlier it seems to me easy but while coding it . I'm bit facing problem such as overflowing content from card in different screensize, cards were not properly responisve . So to fix this. I have done in this way. This was my learning.
```css
@media screen and (min-width:810px) {
    main{
  grid-template-columns: repeat(auto-fit,minmax(10rem,1fr));
        grid-auto-rows: 25rem;
    }
}
```
### Continued development
I am currently learning javascript.

## Author
- Frontend Mentor - [@amandeep2603](https://www.frontendmentor.io/profile/amandeep2603)


