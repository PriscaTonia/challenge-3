# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![images/desktop.png](./screenshot.jpg)
![images/mobile.png](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/PriscaTonia/frontendMentors-challenge-3)
- Live Site URL: [Add live site URL here](https://frontend-mentors-challenge-3.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

During the course of this project, I actually learned quite alot, and some of them are adding a background color and images all together,and positioning the background images using the top, bottom, left and right properties. I never knew you could do that.
I'm still a bit shaky though with my container sizing especially during this project, it actually confused me a lot, but I gave it my all anyways. :)


```css
main{
    min-height: 70vh;
    max-width: 100%;
    background-color:  hsl(185, 75%, 39%) ;
    background-image: url(images/bg-pattern-top.svg), url(images/bg-pattern-bottom.svg);
    background-position:top -70% left 7%, bottom -180% right 7% ;
    background-repeat: no-repeat;
    background-size: 500px, 550px;  
    padding: 90px 500px;
}
/* I'm so proud of this css code above */
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.
- sizing of containers... I mean width and height
-using flex and grid displays
-multiple backgrounds


## Author

- Website - [Onwudebelu Prisca Ebubechukwu](https://www.your-site.com)
- Frontend Mentor - [@PriscaTonia](https://www.frontendmentor.io/profile/PriscaTonia)
- Twitter - [@EbubePrisca](https://www.twitter.com/EbubePrisca)


