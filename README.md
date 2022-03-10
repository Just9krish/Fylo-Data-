# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot 2022-03-08 193557](https://github.com/Just9krish/Fylo-Data-/blob/c3e5f6bf308968affa1b27bebfea5ced3bb239ab/design/desktop-design.jpg)


### Links

- Solution URL: [Click here](https://www.frontendmentor.io/solutions/fylo-data-storage-by-just9krish-fr1_a8i1A)
- Live Site URL: [Click here](https://fylo-data-storage-by-just9krish.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Animation


### What I learned

I learned how to use it to create a animation. I am definitely gonna use it again in the future.



```css
.right-container .meter > span {
  display: block;
  background-image: linear-gradient(
    to right,
    var(--Gradient1),
    var(--Gradient2)
  );
  width: 80%;
  height: 100%;
  position: relative;
  border-bottom-right-radius: 20px;
  border-top-right-radius: 20px;
  border-top-left-radius: 20px;
  border-bottom-left-radius: 20px;
  animation: bar 1.5s;
}

/* Animation */
@keyframes bar {
  from {
    width: 0%;
  }
  to {
    width: 81.5%;
  }
}
/* Animation end */

```


### Continued development

I will continue to learn more about CSS Animation and how it can be used to create a more complex Animation.

## Author

- Frontend Mentor - [@Just9krish](https://www.frontendmentor.io/profile/Just9krish)
- Instagram - [@Just9krish](https://www.instagram.com/just9krish/)
- Linkedin - [@rvamit2648](https://linkedin.com/in/amit-vishwakarma-bb54b222a)

