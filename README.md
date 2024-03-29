# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- View the optimal layout depending on their device's screen size. There are two layouts: mobile and desktop.
- See hover states for interactive elements.

### Screenshots

![screenshot-mobile](images/screenshot-mobile.png)
![screenshot-desktop](images/screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/harnettd/order-summary](https://github.com/harnettd/order-summary)
- Live Site URL: [https://harnettd.github.io/order-summary/](https://harnettd.github.io/order-summary/)

## My process

### Built with

- HTML
- CSS
- Flexbox
- Mobile-first workflow
- Sass
- BEM

### What I learned

In completing this challenge, I learned how to:

- add a box-shadow to a button, *e.g.,*
```css
.payment-btn {
  box-shadow: 0 1rem 1rem $pale-blue;
}
```

- place elements on top of (or underneath) other elements using `position: relatve` and `z-index`, *e.g.,*
```css
.payment-btn {
  position: relative;
  z-index: 1;
}

.cancel-btn {
  position: relative;
}
```

- name classes according to BEM (block, element, modifier) conventions

### Continued development

- There are some aspects of the BEM methodology such as redefinition levels and declarations that I didn't need to learn about for this project. However, I suspect that these ideas will come in handy for larger projects. 

- To build this project, I used a very simple Makefile. I know that there are alternatives better suited to web development such as Gulp. I intend to learn how to use Gulp on a future project.

### Useful resources

- [mdn web docs: box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This is where I learned how to add a box-shadow to an element.

- [Methodology/BEM](https://en.bem.info/methodology/) - This is an excellent resource where you can learn about BEM class-naming conventions and file structure. Other BEM-related topics are covered as well.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.
