# ohmyfood : projet 3 OpenClassRooms WebDev

## Introduction

This website is available at http://ohmyfood.jmax.dev/

This is an OpenClassRooms project, for the web developpers.

The main goal of this project website is to master scss and bem, as well as css animations and transitions.

There is only SCSS and markup in this website, as you can notice if you read this from github.

## 1 homepage, 4 menu-pages

This is my first project with several pages on OpenClassRooms.
I had to focus on only one menu for this work, then copy paste the right names for the others.

## CSS transitions

There are several CSS transitions :

### The "green check div"

Here, on hover is applied a transform: translateX. A check logo also rotates 360deg before coming to its right place on hover in 700ms.
When hover is off, the transition goes smoothly to its original place.

### The heart

this line :

>transition: all 250ms;

makes a second heart appear after 250ms over the first, coloured.

These other lines make the heart appear in linear gradient.

>background: linear-gradient(to bottom left, $primary, $secondary);
>background-clip: text;

### The btn

The button has a transition that makes its color lighter and its shadow darker on :hover

## The animations

### The loader

In this animation there are two animations : 

One for the loader to be proper configured :
The loader is made with an animation. I made a square become a circle using css and thick borders, and then turn on himself. I added colours, the ohmyfood colours, an unusual cubic bezier for it to rotate a complex way.

The other animation is for the page to decrease its opacity.

### The menu to appear progressively

It's a simple game between opacity and transform: translateY.
These properties are in a keyframes and the animation is configured as always in the container element.

## SCSS

This was my first project using SCSS, i admit i love it. The nesting is great, the variables, the mixins are great too.

I used it with BEM for it to complete the nesting