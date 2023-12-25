## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview
A Solution to a Frontend Mnetor Challenge to create a responsive QR-Component for both Desktop and Mobile resolution.
Desktop - 1440px
Mobile - 375px

### Screenshot

![](./images/desktop%20view%20screenshot.png.jpg)

![](./images/mobile%20view%20screenshot.png.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
A container is needed for the contents of the card and another for better positioning especially if the card is not the only content or element in the webpage
```html
<div class="position">
  <div class="content">
    <img src="./images/image-qr-code.png" alt="THE QR Code">
    <h1>  Improve your front-end skills by building projects</h1>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</div>
```
```css
.position{
    align-items: center;
    width: 100vw;
    height: 92vh;
    display: flex;
    justify-content: center;
 }
```
## Author

- Instagram - [Nanji Lakan](https://www.your-site.com)
- Frontend Mentor - [@Shaelle11](https://www.frontendmentor.io/profile/Shaelle11)
- Twitter - [@Nanji Lakan](https://twitter.com/NJamella3)
- LinkedIn - [@Nanji Lakan](https://www.linkedin.com/in/nanji-lakan-theshaelle/)