# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Desktop](/solution/Desktop.png)
![Mobile](/solution/Mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/alangvazq/Challenge01_RSC)
- Live Site URL: [Add live site URL here](https://alangvazq.github.io/Challenge01_RSC/)

## My process

1. Initialize a public repository on [GitHub](https://github.com/alangvazq/Challenge01_RSC).
2. Configure the repository to publish my code to a web address.
3. Look through the designs to start planning out how to tackle the project. 
4. Structure the content with HTML.
5. Write out the base styles for the project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down.

### Built with

- Semantic HTML5 markup
- CSS variables
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

**Variables**

```scss
  $size: 100px;
```

**Interpolation**

```scss
@mixin section($size) {
    $size: 100px;
}
```
```scss
section {
    @include summary_box($size: 200px);
}
```

**Nesting**

```scss
section {
    h1{
        p{

        }
    }
}
```

### Useful resources

- [Example resource 1](https://sass-lang.com/documentation/style-rules/declarations/) - This helped me to learn property declarations.

## Author

- Frontend Mentor - [@alangvazq](https://www.frontendmentor.io/profile/alangvazq)