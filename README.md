# FIGMA 100 Daily UI Challenge

This is a project to code the UI design from the [FIGMA 100 Daily UI Challenge](<https://www.figma.com/file/etUxjWs5vdD10byAOH2zty/100-Daily-UI-Challenge-(Community)?type=design&node-id=0-1&mode=design&t=BAlEtsg11iewlKip-0>), where the platform provides various designs for UI designers to follow or create. Instead, I have taken the step to code them.

## Table of contents

-   [Overview](#overview)
    -   [The design](#the-design)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)

## Overview

### The design

The design task is to create a sign-up page.

### Screenshot

![Result-screenshot](/images/Result.png)

### Links

-   Solution URL: [GitHub Repository](https://github.com/anojumisa/sign-up-page)
-   Live Site URL: [GitHub Page](https://anojumisa.github.io/sign-up-page/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox

### What I learned

Through this project, I gained valuable experience in layering multiple SVG files, a skill particularly useful as the design involved incorporating two layers of SVG files for the background.

As I progressed, I encountered the need to style the placeholder text, which required targeting them specifically rather than solely focusing on the input section. This led me to employ a pseudo-selector tailored for placeholders.

```CSS
input::placeholder {
    font-family: "Montserrat", sans-serif;
    font-size: 12px;
    font-weight: bold;
    color: #533ede;
}
```

Additionally, I refined the text's appearance by utilizing the letter-spacing property, aiming to closely match the design's aesthetic.

```CSS
h1 {
    font-family: "Montserrat", sans-serif;
    font-size: 35px;
    font-weight: normal;
    letter-spacing: 4px;
    color: #ffffff;
    width: 250px;
    margin-bottom: 0px;
    padding-left: 2em;
}
```

### Continued development

I aim to enhance my comfort level with flexbox and CSS by experimenting with their properties, given the multitude of functions that require a thorough understanding.

## Author

-   Website - [Ano Jumisa](https://www.anojumisa.com)
-   GitHub Page - [Ano Jumisa](https://github.com/anojumisa)
-   Twitter - [@anojumisa](https://www.twitter.com/anojumisa)
