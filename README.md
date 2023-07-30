# Project 2 - Integrate a mobile website with animations in CSS
## Introduction
This website is available at https://rujalb.github.io/
This is an OpenClassRooms project, for the web developpers.
The main goal of this project website is to master css animations and transitions.

## 1 homepage, 4 menu-pages
I had to focus on only one menu for this work, then copy paste the right names for the others.

## CSS transitions

There are several CSS transitions :

### The "green check div"

Here, on hover is applied a transform: translateX. A check logo also rotates 360deg before coming to its right place on hover in 750ms.
When hover is off, the transition goes smoothly to its original place.

### The heart

this line :
>transition: all 0.2s;
makes a second heart appear after 0.2s over the first, coloured.
These other lines make the heart appear in linear gradient.

### The btn
The button has a transition that change its color lighter on :hover

## The animations
### The loader
The loader is made with an animation. 

### The menu to appear progressively
It's a simple game between opacity and transform: translateY.
These properties are in a keyframes and the animation is configured as always in the container element.
