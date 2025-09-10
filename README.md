## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:

### Built with

- Semantic HTML5 markup
- CSS custom properties
- grid
- flexbox
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

main > h1 {
width: 70%;
text-align: center;
background-clip: text;
-webkit-background-clip: text;
color: transparent;
background-image: linear-gradient(90deg, #FFEB3B, #00BCD4);
text-transform: capitalize;
font-weight: 800;
margin: 0px auto 40px;
padding-top: 30px;
line-height: 1.1;
transform: rotateX(90deg);
transform-origin: top;
transition: all 0.5s;
}
main:hover h1 {
transform: rotateX(0deg);
}
@media (min-width: 769px) {
main > h1 {
margin-bottom: 30px;
padding-top: 0;
font-size: 35px;
}
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
