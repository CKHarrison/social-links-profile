# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/example-screenshot.png)

### Links

- Solution URL: [Frontend Mentor](https://your-solution-url.com)
- Live Site URL: [Github pages](https://www.ckharrison.github.io/social-link-profile)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I used this project as a reinforcement of how to use @font-face imports and to remember how to do css animations, it's been a while!

```css
.link {
  background-color: var(--color-grey-750);
  border: none;
  border-radius: 0.5rem;
  color: var(--color-white);
  font: var(--text-preset-2-bold);
  padding: 0.75em 1.5em;
  width: 100%;
  text-decoration: none;
  transition: all 0.5s ease;
}

.link:visited {
  color: var(--color-white);
}

.link:hover,
.link:hover:visited,
.link:active,
.link:focus {
  background-color: var(--color-green);
  color: var(--color-grey-750);
}
```

### Continued development

I plan on to continue working on creating more complicated CSS animations in the future. While I don't plan on using complex animations regularly, it's probably worth becoming proficient in them anyway.

### Useful resources

- [CSS Tricks](https://css-tricks.com/almanac/properties/t/transition/) - The always useful CSS Tricks provides an easy and quick reference on how to use transitions.

## Author

- Website - [Chris Harrison](https://www.charrison.dev)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/CKHarrison)
- GitHub - [@CKHarrison](https://github.com/CKHarrison)
