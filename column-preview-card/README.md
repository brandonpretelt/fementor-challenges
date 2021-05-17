# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover states for interactive elements

### Screenshot

[Column Preview Card Desktop Solution](https://raw.githubusercontent.com/brandonpretelt/fementor-challenges/second-challenge/column-preview-card/column-preview-card-desktop-solution.png)

[Column Preview Card Mobile Solution](https://raw.githubusercontent.com/brandonpretelt/fementor-challenges/second-challenge/column-preview-card/column-preview-card-mobile-solution.png)

### Links

-   Solution URL: [Column Preview Card Component Solution](https://www.frontendmentor.io/solutions/3-column-card-component-using-sass-QHVR4WaFX)

-   Live Site URL: [Column Preview Card Component Live Site](https://brandonpretelt.github.io/fementor-challenges/column-preview-card/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS Grid & Flexbox
-   Mobile-first workflow
-   [Sass](https://sass-lang.com) - Syntactically Awesome Style Sheets

### What I learned

The biggest takeaway that I learned from this project is how important it is to style the content first and focus on the layout. This is actually a mix of a lesson that I learned from watching [Kevin Powell](https://youtube.com/kevinpowell) and by working on this project. What I mean by this is is this: I was working on the hover for the desktop solution and what ended up happening was I had a border\* set to 2 pixels on hover and when I hovered, it shifted the content sections up and then back to normal afterwards. I thought it was a weird behavior and so, I went through the dev tools to see what was up. It appeared that I had set a line-height set somewhere that wasn't supposed to be there. So, I deleted it and it fixed up layout issue. So, I think that I definitely learned there how important it is to focus on content issues first before trying to work on the layout.

Something less major that I learned is how to work with Sass again. I haven't really touched Sass much but, I decided to use it for this project. Something that I liked and totatally forgot that I could was set a pseudo element by adding the &amp;: in a nested element. What I mean by that is this:

```css
section {
    &:first-child {
        /*** css code here ***/
    }
}
```

I thought that was pretty neat.

### Continued development

I think that going forward, as explained above, focusing on styling content first is going to be my priority. I think I'll do this by using [@kittygiraudel](https://twitter.com/KittyGiraudel)'s 7-1 pattern in Sass. Essentially, what this is is a way to structure your Sass into 7 different folders and bring them all into your main sass file. What this does is makes everything more organized. By doing this, you can a folder for your utility classes (think variables partial) or a place for all your typography styles. What I want to do with this is modify it a bit and have it work for my needs. So that way, I can have a more content-first approach to styling. This will also help out with my organization issues, as well.
