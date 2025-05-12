# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./preview.jpg)

*Note: Take a screenshot of your solution and add it to the project. You can use browser tools to capture the screenshot, then crop and add it to your project directory.*

### Links

- Live Site URL: [NFT Preview Card]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts - Outfit font family

### What I learned

This project helped me practice creating a responsive card component with hover effects. I particularly enjoyed implementing the image overlay effect that appears when hovering over the NFT image.

Some code snippets I'm proud of:

```html
<div class="image-container">
  <img src="./images/image-equilibrium.jpg" alt="Equilibrium NFT" class="nft-image">
  <div class="overlay">
    <img src="./images/icon-view.svg" alt="View" class="view-icon">
  </div>
</div>
```

```css
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: hsla(178, 100%, 50%, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.image-container:hover .overlay {
  opacity: 1;
  cursor: pointer;
}
```

### Continued development

In future projects, I'd like to focus on:
- Improving my CSS animations and transitions
- Learning more about accessibility best practices
- Exploring CSS Grid for more complex layouts

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive reference for HTML, CSS, and JavaScript.
- [CSS-Tricks](https://css-tricks.com/) - Great articles and guides for CSS techniques.

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)


## Acknowledgments

Thanks to Frontend Mentor for providing this challenge and to the Frontend Mentor community for their support and feedback.
