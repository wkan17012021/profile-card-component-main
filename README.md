# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

This is an interesting challenge as it appears to be a common feature amongst online profiles. The aim was to again maintain proficiency with the reproduction of the template.
11/02/2022: the first attempt wasn't great. With feedback from the FEM community and youtube, I revised this card component almost in its entirety. The html structure this time round, had the card component split by the bubble header section, a wrapper for the image, main body or central content followed by a use of ul->li tags for footer notes (thanks Vanza Setia). The layout is more responsive: it still requires a lot of tweaking with margins, a little bit of padding (use media query on the card container to set min-width for transition from mobile to big screen). The bubble background works now at mobile view but still don't know how to set it so they maintain the position when the screen width is extended to the desktop.

### The challenge

- Build out the project to the designs provided

## My process

- Use a similar layout process as before- box model for the outer container, a div or section for the upper background image.
- Position relative for the central profile photo, then trial and error margin settings for the main text beneath. This seems like a "hacky" way to do this, perhaps there is a cleaner process.
- Background overlay with trial and error for the positioning.
- Flex for the stats / social media details.

- See above 11/02/2022

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Conscious of overrunning time for this challenge. Need to research how to fine-tune the background pattern so that it can be rendered as per the template. Possibly a combination of background-repeat/position/size properties. Also, the positioning of the circle photo I feel is perhaps not the conventional way of rendering this feature- perhaps some combination of margins (negative?) and z-index.
Finally, the responsiveness is a bit jarring, still working on a way to improve this.

- See Overview 11/02/2022

### Continued development

- Learn to manipulate background properties styling.
- Learn how the profile photo is typically rendered.

### Useful resources

- The odd stack overflow query and W3 consultation.
- FEM community (@vanzasetia) and youtube (Coding Sections).

## Author

wkan17012021

## Acknowledgements

- https://www.youtube.com/watch?v=vjObtWO5RvU&t=11s&ab_channel=CodingSections
- https://www.frontendmentor.io/solutions/profilecardcomponent-1Zt2mRXoR#comment-6205b84f6d85946804df72fc
