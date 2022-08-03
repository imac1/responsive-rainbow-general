# Responsive Rainbow

## Story

To impress users, you need something extra nowadays. Some rainbows, for example.

Create a small site that changes a few details when the user resizes the window.

Expected result: https://www.youtube.com/watch?v=JmkdB7O1ukI

## What are you going to learn?

- Use basic @media queries in CSS.
- [re-]Position elements. 

## Tasks

1. Extend the default CSS file to change the background based on the width of the browser window. When the user resizes the browser window, the background must change. Use colors from [materialpalette.com](https://www.materialpalette.com/colors), and breakpoints of 50px starting from 600px width.
    - When opening the site in a window smaller than 600px in width, the background is red.
    - When opening the site in a window at least 600 pixels in width, the background is orange.
    - When opening the site in a window at least 650 pixels in width, the background is yellow.
    - When opening the site in a window at least 700 pixels in width, the background is green.
    - When opening the site in a window at least 750 pixels in width, the background is blue.
    - When opening the site in a window at least 800 pixels in width, the background is indigo.
    - When opening the site in a window at least 850 pixels in width, the background is purple.

2. Align the hint box to be on the top center by default. For devices capable of displaying more than 550px in height, place the hint box in the middle of the page. For 650px+, move it to the bottom of the page.
    - When opening the site in a window smaller than 550px in height, the hint box is located in the top of the page.
    - When opening the site in a window at least 550px in height, the hint box is in the middle of the page.
    - When opening the site in a window over 650px in height, the box is in the bottom of the page.

3. For a smooth experience, change values using `transition`.
    - Resizing the page changes the background color over 1 sec.
    - Resizing the page moves the hint box over 1 sec.

## General requirements

- Try to split up the problem into small pieces and try to solve them before Googling.
- The default HTML code is not modified.
- No 3rd party libraries are used.

## Hints

- Don't overthink the task. If you get stuck in trying, just try to look at the problem from a different perspective.

## Background materials

- <i class="far fa-exclamation"></i> [Media Queries Explained](https://medium.com/@pbojinov/media-queries-explained-9bf20a85731f)
- <i class="far fa-exclamation"></i> [CSS transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
