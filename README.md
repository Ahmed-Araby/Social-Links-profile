# Social links profile

This is my solution for the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview
The Social Links Profile challenge is about creating a card ceneterd in the middle of the screen, the card includes information about the user and links to his profiles on professional platforms like LinkedIn, GitHub, Frontend Mentor, etc....

### Screenshot
#### Desktop viewport
![page-in-desktop-viewport.png](https://github.com/Ahmed-Araby/Social-Links-profile/blob/main/documentation/images/page-in-desktop-viewport.png)

#### Tablet viewport
![page-in-tablet-viewport.png](https://github.com/Ahmed-Araby/Social-Links-profile/blob/main/documentation/images/page-in-tablet-viewport.png)

### Mobile viewport
![page-in-mobile-viewport.png](https://github.com/Ahmed-Araby/Social-Links-profile/blob/main/documentation/images/page-in-mobile-viewport.png)

### Links

- Solution URL: [https://github.com/Ahmed-Araby/Social-Links-profile](https://github.com/Ahmed-Araby/Social-Links-profile)
- Live Site URL: [https://ahmed-araby.github.io/Social-Links-profile/](https://ahmed-araby.github.io/Social-Links-profile/)

## My process
* define the design system using css variables and classes.
* set global styles.
* layout the HTML structure.
* style for the mobile view port, then the tablet viewport and lastely the Desktop viewport.
* document and deploy my solution.
  
### Built with
- Semantic HTML5 markup
- Flexbox
- CSS variables
- Media Queries
- custom variable font file


### What I learned
- defining media query breakpoints for the different viewports / screens that I want to support.
- using relative units em and rem instead of the static px to adapt with the user changes to the browser default font size.
- vertical padding (and probably also vertical margin) of inline elements are not respected / recognized by the surrounding elements.
- specifying a path to a resource with a leading forward slash like this **/assets/images/avatar-ahmed.jpeg** will be considered the path of the resource from the domain where the page was loaded from. instead if the asset should be loaded relative to the url where the page was loaded from, the asset path should be specified without leading forward slash.
