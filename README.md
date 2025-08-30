# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![](./preview.jpg)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

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


## Acknowledgments

Thanks to Frontend Mentor for providing this challenge and to the Frontend Mentor community for their support and feedback.
