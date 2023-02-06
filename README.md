# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/qr-code-component.png)

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

- Mobile-first workflow

### What I learned

The card is simple and minimalist but a project that I thought would take 5 minutes to do ended up took me longer.
The problem is I was reproducing a copy and to find out how much of padding and how much of margin and leaving everything in harmony are small details that takes time.

The HTML was very simple

```html
<div class="container">
  <div class="card">
    <img src="./images/image-qr-code.png" alt="image of qr-code" />
    <div class="text-card">
      <h2></h2>
      <p></p>
    </div>
  </div>
</div>
```

CSS I used root variables

```css
root {
  --white-color: hsl(0, 0%, 100%);
  --lightGray-color: hsl(212, 45%, 89%);
  --grayishBlue-color: hsl(220, 15%, 55%);
  --darkblue-color: hsl(218, 44%, 22%);
}
```

<!--
```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
``` -->

### Continued development

I'm pretending to do another card but using react and it generate QR-Code

### Useful resources

- [w3schools](https://www.w3schools.com/) - When I don't know something I can always have a light here.

## Author

- Website - [Andreas Ziegler](https://github.com/Andreas-Ziegler22)
- Frontend Mentor - [@Andreas Ziegler](https://www.frontendmentor.io/profile/yourusername)
