# HACKTOBER FEST 2023 WEB DEV

This is a solution to the Problem statement given in the HACKTOBERFEST 2023

## Table of contents

- [HACKTOBER FEST 2023 WEB DEV](#hacktober-fest-2023-web-dev)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview
  This is the solution of the problem given in the Hacktoberfest 2023.


### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot
![screenshot](<images/Screenshot 2023-10-15 220053.png>)
![screenshot](<images/Screenshot 2023-10-15 220129.png>)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned to use the adjacent sibling selector to make the view icon appear on hover.

.view {
  display: none;
}
.image-container:hover .overlay + .view {
  display: block;
}


### Continued development

For future projects I need to focus on using more advanced CSS to create effects.

### Useful resources

-How To Create an Overlay Image Icon(https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me to add an overlay to the image on hover.
-Using only CSS, show div on hover over another element (https://stackoverflow.com/questions/5210033/using-only-css-show-div-on-hover-over-another-element)- This Stack Overflow question helped me to figure out how to show the view icon on hover.

## Author

- Frontend Mentor - [@yashraj4823](https://www.frontendmentor.io/profile/yashraj4823)
- GitHub - [@yashraj4823](https://github.com/yashraj4823)


