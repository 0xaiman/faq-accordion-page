# Frontend Mentor - FAQ accordion solution

This is my attempt at solving the Frontend Mentor Challenge , [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). 

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
  The challenge ask you to create an accordion for FAQs page. From what I have seen, it is easier to start from mobile then port to desktop display. 

### The challenge

#### 1. Dropdown effect
I have the gist of idea that in order to apply "responsive-ness" of the dropdown, scripting is required.

This is done by applying trigger and detect them using onClick or eventListener to toggle class.

when the class is applied, the styling asscosciated with the class will appear.

`For example;
class=" dropdown"

/* apply click event*/

class="dropdown activated".

resources referred are: 
[FAQ Accordion | Frontend Mentor Challenge (HTML, CSS, and JS)](https://www.youtube.com/watch?v=HJuD66J7uCE)

#### 2. Container position

This is more of a pet peeve.

The other issue, is that the position of the container , is centered when not activated. this causes a gap between the header image and the container.

<img src='/screenshot/1 not corrrect centered.png'>

This happens because the following styling is applied.(on body element)
<img src="/screenshot/body wrong.png">

To correct this, it is better to use the following

<img src="/screenshot/body correct.png">

This will push the container to topmost of the screen, but this can be fix using margin-top.
<img src="/screenshot/1.png">




