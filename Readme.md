https://github.com/hiteshchoudhary/js-hindi-youtube/blob/main/07_projects/projectsset1.md

# JavaScript Background Color Switcher

## Overview

This project demonstrates a simple JavaScript application that allows users to change the background color of a webpage by clicking on color buttons. The color options are presented as clickable blocks, each representing a different color.

## Features

- Clickable color buttons to change the background color of the page.
- Simple and clean design for easy use and understanding.

## Files

- `index.html` - The HTML file containing the structure of the webpage.
- `chaiaurcode.js` - The JavaScript file that handles the background color change logic.
- `style.css` - The CSS file that provides styling for the buttons and layout.


JavaScript Code
The chaiaurcode.js file contains the following code:

```javascript
const buttons = document.querySelectorAll('.button');
const body = document.querySelector("body");

buttons.forEach(function(button){
  button.addEventListener('click', function(e){
    body.style.backgroundColor = e.target.id;
  });
});
```
