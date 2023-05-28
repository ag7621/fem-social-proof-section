# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Desktop preview image for Social proof section challenge](/images/desktop-preview.png "Desktop preview")
![Mobile preview image for Social proof section challenge](/images/mobile-preview.png "Mobile preview")

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

This challenge took me much longer than I was hoping for, however it gave me a great deal of practice implementing responsiveness into my design.

Initially I had built the site with the desktop view in mind as it seemed more complex of the two, but as I moved onto the mobile view I fell into some complications having to overwrite certain styling in the media query adding to a lot of bulky code. Instead I rewrote it by moving a good portion of the desktop view into the media query and set up the base code with mobile defaults.

I had also started using Grid instead of Flex to make the site, but ran into issues trying to make it reponsive. I believe it was because of the rigid nature to which I started with, overly declaring a lot of padding and margins to position elements in as closely as I could with the reference images. This led to a lot of frustration to which I remedied with going back to using Flex. Despite losing the experience developing with Grid I did gain more experience in Flex which I still count as a win.



### Continued development

One thing I've come across a lot in these challenges is how the colors chosen in the challenge often have accessibility conflicts which I'm not sure how to properly address. I'd like to find solutions from other frontend mentor users to see how they addressed these issues, but for the most part everyone follows the design patterns. I wonder if this is the nature of web development or something that can be alleviated in some way I have yet to learn. I've tried adjusting color contrasts before but the colors stray too far away from the design that I'm unsure what to do.

As always practicing building responsive sites is something on my list and will continue to practice. As I've continued with these challenges I think I'm becoming more familiar in how to approach it, but it will something I'll continue to practice. 

I had come across a comment about using figures for the quote section, however having never used figures before I wasn't entirely sure how to implement it. Accessibility properties in the Firefox dev tools suggest I did not do it correctly. This is something else I would like to look further into when it comes to more complex design patterns.

### Useful resources

- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.
- [Kevin Powell - 3 modern CSS techniques for responsive design](https://youtu.be/VsNAuGkCpQU) - This video came in really handy when I was figuring out ways to make the main headline font responsive with the design in using the clamp function.
- [Utopia - Fluid Responsive Design](https://utopia.fyi/) - This is the site mentioned in Kevin Powell's video which aids in fluid responsive typography and spacing.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)
