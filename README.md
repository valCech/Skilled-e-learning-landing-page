# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot 2022-07-12 at 08-56-16 Document](https://user-images.githubusercontent.com/102651272/178440139-eb5cc468-666e-47a6-8228-a42609721adc.png)
![Screenshot 2022-07-12 at 08-57-56 Document](https://user-images.githubusercontent.com/102651272/178440196-13c996e1-f061-4964-84d3-6dfe775b0a83.png)
![Screenshot 2022-07-12 at 08-58-39 Document](https://user-images.githubusercontent.com/102651272/178440260-ed6d6ae5-4163-4da9-bd27-39a3b66710b0.png)


### Links

- Solution URL: https://github.com/valCech/skilled-elearning-landing-page/


## My process

First I built it with Flex for mobile version. It was then impossible to connect 2 and later even 3 sections as the resolution was growing. I had to delete it all and start again but from desktop size. This time I used also a grid technique.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first work flow




### What I learned

I did master "know how" to use responsive images.

To see how you can add code snippets, see below:
```HTML
<picture> 
        <source
          srcset="img/image-hero-desktop.png"
          media="(min-width: 1400px)"
        />
        <source 
          srcset="img/image-hero-tablet.png" 
           media="(min-width: 1000px)" 
        />
        <img
          class="hero__img"
          src="img/image-hero-mobile.png"
          alt="ladie browsing on laptop"
        />
      </picture>
```

### Continued development

I want to focus more on Grid as it helped me a lot where the Flexbox was strugglin. 
For example nav is better build with flex whether main layout is better build w grid

### Useful resources

My school notes, 
Powell Kevin for Grid


## Author


- Frontend Mentor - (https://www.frontendmentor.io/profile/valCech)
- Twitter - [Vlastimil Slechta](@VlastimilSlech1)




## Acknowledgments

Also big thanks to Prantik Noor for helping me with the final polishing despite I asked him randomly on Slack. Thank you sir!
