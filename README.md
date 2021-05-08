# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
    
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size

### Screenshot

[Mobile view](https://imgur.com/a/Rca8Ldm)]
Mobile view

[Mobile view](https://imgur.com/a/61QHcsu)
Mobile view

[Desktop view](https://imgur.com/a/5mAfIpr)
Desktop view

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)

-   Live Site URL: [Live Solution](https://brandonpretelt.com/festatspreviewcard/index.html)

## My process

### Built with

-   HTML5
-   CSS custom properties
-   CSS Grid & Flexbox
-   Mobile-first workflow
-   BEM (Block, Element, Modifier) Naming Convention

### What I learned

Something that I learned while working on this project is how to do a CSS color image overlay. The following code, which I found in my research on how ot learn how to do said overly, does the following: The first part of it targets the direct child of hero section and gives it a width of 100%, hides any overflow and gives it a background color (which is the nice purple color from the style guide). Then you select the image you want to overlay, in my case, I just selected the a "general" img descendant of the .hero-section class. The object-fit, as I understand it, makes sure that image tag can fill its container depending on the value you give it. For example, in this case, I have an object-fit of cover. What this does is makes sure the image keeps its aspect ratio and dimensions, however, it also allows the image to crop to fill the remaining space. My only regret is that I barely modified the below code before using it as my own. Just made a slight tweak.

```css
.hero-section > .hero-section__overlay {
    width: 100%;
    overflow: hidden;
    background-color: var(--clr-violet-277-40);
}

.hero-section img {
    object-fit: cover;
    opacity: 0.3;
}
```

Something else that I managed to learn or, at the very least, tried to implement was the BEM method of naming classes. I have long since struggled with coming up with a proper naming scheme for classes. BEM, for me, is a great solution so that I don't have an excuse to name things poorly. I admit, though, that I still have a long way to go in this regard but, I think that I did pretty well in terms of naming.

A lot of the work that I did here was more of a review for me since I haven't picked up HTML/CSS/Front End development in a long while.

### Continued development

Naming conventions and understanding CSS is where I could gain to stand more experience in. Definitely going to be relearning a bunch of stuff from here on out.

### Useful resources

-   [Achieve Image Colour Overlay CSS](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) - This is the resource I mentioned about a color overlay on an image. It's a pretty nice read.

-   [Build Responisve Images](https://www.sitepoint.com/how-to-build-responsive-images-with-srcset/)
    This source reminded me how to do some responsive images. I did something similar in school but, I've forgotten due to my lack of practice. It's a great resoource.

## Acknowledgments

Thanks to [ellen_dev](https://twitter.com/ellen_dev), I was able to get that overlay.

Thanks to [@saurabhkirtani](https://twitter.com/saurabhkirtani) for the wonderful Sitepoint article on responsive images.
