# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The challenge was to build out the product preview card component and get it looking as close to the design as possible.
The designs of the projects are inside the `/design` folder. Both a mobile and a desktop version of the design are in JPG static format. Using JPGs mean that styles such as `font-size`, `padding` and `margin` are not given and had to be guessed.

End users should be able to:
- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop

![](./images/Screenshot_Desktop.png)

Movile

![](./images/Screenshot_Movile.png)

### Links

- Solution URL: [GitHub Solution](https://github.com/JordanBichot/product-preview-card-component-main.git)
- Live Site URL: [Live Site](https://fem-product-preview-card-challenge.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Continued development

Currently, the old price (169.99) is not being properly announced to screen readers. To fix this, the price needs to be wraped in a del element and inside it add a span element with an sr-only class and the text “Previous price”, then using CSS the del element can be made only visible to screen readers.

### Useful resources

- [Josh's Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This Reset uses a more-intuitive box-sizing model. Removes default margin. Allows percentage-based heights in the application. Adds accessible line-height. Improves text rendering. Improves media defaults. Removes built-in form typography styles. Avoids text overflows and, if needed create a root stacking context.
- [Taking on a Frontend Mentor challenge | Responsive Product Preview Card Component](https://youtube.com/watch?v=B2WL6KkqhLQ&feature=shares) - This is a video that explains step by step how to solve this challenge.

## Author

- Jordan Miguel Bichot Pérez - [FinTech Samurais](https://fintechsamurais.com/)
- Frontend Mentor - [@JordanBichot](https://www.frontendmentor.io/profile/JordanBichot)
- GitHub - [@jordanbichot](https://github.com/jordanbichot)
- LinkedIn - [Jordan Miguel Bichot Pérez](https://www.linkedin.com/in/jordan-miguel-bichot-p%C3%A9rez-613172225)
- Twitter - [@BichotJordan](https://twitter.com/BichotJordan?t=lu5q3WUeYHh3oWaySHXjIg&s=09)

## Acknowledgments

Thanks to the invaluable help of my mentor and friend [Dariel Medina Rodríguez](https://github.com/darielmedr)
