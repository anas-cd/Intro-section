# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5).
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/images/finished.png)

### Links

- Solution URL: [https://github.com/anas-cd/Intro-section](https://github.com/anas-cd/Intro-section)
- Live Site URL: [https://anas-cd.github.io/Intro-section/](https://anas-cd.github.io/Intro-section/)

## My process

### Built with

- html
- CSS and scss custom properties
- Flexbox


### What I learned

there are two ways I can make the dropdown menu using only CSS, 

1- by using input type of checkbox 
2- by using css naibor selector and pointer events 

got a link for both methods in the resources 

### Useful resources

- [css only dropdown menu using input checkbox](https://youtu.be/POxn1x3kAyY) - This method worked fine for opening and closing the dropdown menu, this is the better method in my opinion since it can be nested and will still work if we got multiple nested dropdown submenus.
- [Pure CSS Onclick Dropdown Menu](https://lage.us/CSS-Onclick-Dropdown-Menu.html) - This method works well on dropping down the menue, but when the menu is down you lose the ability to have any control over the mouse and its effects like 'cursor:pointer' on the focused element, so to overcome this issue you need to wrap the dropdown menu in a div so you can make the pointer appear on when the dropdown menu is focused on, also this method is not good at nested dropdown menus because as soon as the user clickes on any link or another nested dropdown menu it will close since the focus is gone on the original menu.


## Author

<!-- - Website - [anas ali](https://www.your-site.com) -->
- Frontend Mentor - [@anas-cd](https://www.frontendmentor.io/profile/anas-cd)
- Twitter - [@AnasCd](https://twitter.com/AnasCd)
