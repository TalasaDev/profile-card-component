# profile-card-component
Frontend Mentor NEWBIE FREE Challenge

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
  
## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![image](https://user-images.githubusercontent.com/119393713/205567447-34900b3e-0637-4906-8e25-6620819f6022.png)



### Links

- Solution URL: [https://github.com/TalasaDev/profile-card-component](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge I learned how to:

- add a background image as "banner" by creating an empty <div class="banner"> container and styling it in the style.css using the .background-image property.

```` HTML

<main>    
    <div class="banner"></div>

```` CSS

.banner {
  background-image: url(./images/bg-pattern-card.svg);
  height: 23vh;
  width: 100%;
  border-radius: 10px 10px 0 0;
}

It is important to remember when using this approach to add height to the .banner container, otherwise it won't be seing. 

- style an image to get it to look like it was between to sections of the HTML. To do so, I applied a negative top margin.

```` HTML

<div class="img-wrap">
     <img src="./images/image-victor.jpg" alt="man profile picture">
</div>

```` CSS

.profile .img-wrap {
  position: relative;
}
.profile img {
  border-radius: 100%;
  margin-bottom: 20px;
  margin-top: -50px;
  border: 5px solid white;
  width: 100px;  
}

### Continued development

advanced CSS and frameworks.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@talasa-dev](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

