# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Author](#author)


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./ScreenShot.png)

### Links

- Solution URL: [https://github.com/macdeesh/Stats-Preview-Card-Component]
- Live Site URL: [https://macdeesh.github.io/Stats-Preview-Card-Component/]

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

- I learned how to use different picture format by using:

  ```
  <picture>
  <source srcset="./second image.jpg" media="(min-width:900px)">
  <img src="./first image.jpg" alt="#" class="#">
  </picture>
  ```
  
- I learned also to change the color of the image first with :

```
image {
  filter: opacity(0) drop-shadow(0 0 0 color)
  saturate() contrast() brightness() grayscale();
  }
```
  
- Then I choose to use something else that i learned, by applying ```mix-blend-mode: multiply;``` css property on a CHILD element inside PARENT element with a background property ```background-color``` and ```display: block;``` to fill all the place.

### Useful resources

- [https://www.w3schools.com/cssref/pr_mix-blend-mode.asp]- This helped me to understand and use the mix blend mode.
- [https://www.w3schools.com/tags/att_source_srcset.asp]- This helped me to understand and use the HTML <source> srcset Attribute.


### Author

- Github - [Macdeesh](https://github.com/macdeesh)
- Frontend Mentor - [@macdeesh](https://www.frontendmentor.io/profile/macdeesh)
- Twitter - [@Macdiish](https://twitter.com/Macdiish)
