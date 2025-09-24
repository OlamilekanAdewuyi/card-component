# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot
![](./Screenshot 2025-09-23 194005.png)

### Links
- Solution URL: [Add solution URL here](https://github.com/OlamilekanAdewuyi/card-component.git)
- Live Site URL: [Add live site URL here](https://card-component7.netlify.app/)


## My process

### Built with
- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox and CSS Grid for layout
- Media queries for responsiveness
- Google Fonts (Poppins)

### What I learned
From this project, I learned how to structure my HTML and style it with CSS to create a neat design. I also practiced using media queries to make the layout responsive across different devices. This helped me understand how important responsiveness is when building modern webpages.

```css
@media screen and (max-width: 600px) {
  main {
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .header-txt1 {
    font-size: 1.5rem; /* smaller title */
    text-align: center;
  }
  .header-text h2 {
    font-size: 1.4rem;
  }
  .header-paragraph-txt{
    width: 90%;
    padding: 0 10px;
    font-size: 0.9rem;
    line-height: 1.4;
    margin-bottom: 50px;
  }
  section {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    align-items: center;
  }
  .box1,
  .box2,
  .box3,
  .box4 {
    width: 100%;
    max-width: 320px;
    padding: 20px;
  }
  .box1 img,
  .box2 img,
  .box3 img,
  .box4 img {
    width: 40px;
    height: 40px;
  }
  section p {
    font-size: 0.85rem;
    width: 100%;
  }
}

## Continued development
For continued development, I want to keep improving my responsiveness skills by practicing how layouts adapt across different screen sizes. I also plan to refine my use of media queries, experimenting with multiple breakpoints to make designs smoother and more consistent. Additionally, I’d like to focus more on accessibility and clean code practices, ensuring that my projects are both user friendly and maintainable.

## Author
- Frontend Mentor - [@Olamilekan](https://www.frontendmentor.io/profile/OlamilekanAdewuyi)
- Twitter - [@olamilekan_lcc](https://x.com/Olamilekan_lcc?t=bqsjVbUEQQjksZTp4RRb_Q&s=09)
