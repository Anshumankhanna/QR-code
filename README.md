# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

Creating my first ever QR code file

### Screenshot

![Alt text](Desktop-view-capture-1.png)
![Alt text](Mobile-view-capture-1.png)

<!-- Taken using Go Full Page chrome extension -->

### Links

- Solution URL: https://github.com/Anshumankhanna/QR-code
- Live Site URL: https://anshumankhanna.github.io/QR-code/

## My process

First create a div section class="qr-space" that will be the floating box of QR code
Set the properties of body
Set the properties of div.qr-space
Then create two div sections; class="image" and class="text"
In the div.image we put the image, adjust it's dimensions and properties
In the div.text we already have the text but the text has two paragraphs with different properties and hence we again seperate it using two div sections -> class="bold-text" and class="light-text"
We set the shared properties of both div.bold-text and div.light-text and seperate properties
For font we import a variable font family and use @font-face to set a custom font
This font is set for div.text
Lastly using @media Mobile view is set just adjust div.qr-space top margin, reducing it

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned to use div sections in a better way

Finally understood how to use @media, a key point I learnt is to cause a change a change at 375px I needed to give value of 376px something I had not understood while making an other project

```
@media only screen and (max-width: 376px){
    .qr-space {
        margin: 100px auto auto;
    }
}
```

Learnt how to add fonts using a file and create custom fonts

```
.text {
    flex-direction: column;
    font-family: "Outfit";
}

@font-face {
    font-family: 'Outfit';
    src: url("Outfit-VariableFont_wght.ttf");
}
```

Improved my understanding of display: flex and related properties such as align-items

### Continued development

Want to learn how to make more responsive layout using just CSS and understand div sections in even further detaile

### Useful resources

- ChatGPT for syntax clarifications and understanding some values

## Author

- Website - Anshuman Khanna
- Frontend Mentor - @Anshumankhanna (https://www.frontendmentor.io/profile/AnshumanKhanna)

## Acknowledgments

I have only myself to thank B)
