# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/profile-card-demo.png)


### Links

- Solution URL: [View Solution on FEM](https://www.frontendmentor.io/solutions/profile-card-component-using-sassscss-flexbox-and-grid-7-E2CjaFZ)
- Live Site URL: [View Live on Github Pages](https://perezjprz19.github.io/FEM-profile-card-component-main/)

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass

### What I learned

- For this project I used Sass for the first time. I learned to install node-sass and how to write my styles in sass syntax.

- I learned about Sass variables, Sass functions, Mixins, and partials.

- When I was building this project, I found that there was an inconsistency with the way the images were being accessed on Github vs. how they would be accessed locally. Basically, because I had created a new folder for all my styles, I would need to write the path as /images/something.svg and this would allow the image to be displayed locally as a background image. However, when launched through Git Pages, the images would not appear in the viewport. The way to resolve this was by writing the path this way: ../images/something.svg. Notice that there are two dots prior to accessing the image folder.

- minmax() is to be used with Grid.

### Continued development

- I want to get more comfortable with SASS functions and best nesting practices. Even though SASS makes it easy to organize CSS, I still felt like it was a mess.

- I want to dedicate more time to get current with the new SASS features.

- I want to get familiar with the command line. I feel like I'm missing out on a lot of features by not using the command line, especially with managing my Github.

### Useful resources

- [Learn Sass in 20 Minutes | Sass Crash Course](https://youtu.be/Zz6eOVaaelI) - This video was very helpful in getting me started quick while still having a basic understanding of what I can do with Sass.

- [When Sass and New CSS Features Collide](https://css-tricks.com/when-sass-and-new-css-features-collide/#:~:text=The%20trick%20here%20is%20to%20remember%20that%20Sass,it%E2%80%99s%20still%20valid%20CSS%20that%20works%20as%20intended.) - This article was very helpful in helping me work through some of the errors I was receiving while compiling my code. I couldn't understand why min() and max() were not working with different units when I was certain it should.

## Author

- Frontend Mentor - [@perezjprz19](https://www.frontendmentor.io/profile/perezjprz19)
- Twitter - [@t0xicm0nkey93](https://www.twitter.com/t0xicm0nkey93)
