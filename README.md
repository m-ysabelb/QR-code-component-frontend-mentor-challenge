# Frontend Mentor - QR code component solution by @m-ysabelb

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot of the solution](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Code Snippet Takeaways](#code-snippet-takeaways)
  - [Continued development](#continued-development)
  - [References](#references)
- [Author](#author)
- [Acknowledgment](#acknowledgment)

## Overview
This challenge is great for HTML and CSS starters. The card layout doesn't shift, so it is ideal for those who haven't learned about building responsive layouts yet.


### The challenge
[QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)

### Screenshot of the Solution
[Desktop view](./screenshots/Desktop%20view%20-%20QR%20component.jpeg)

[Mobile view](./screenshots/Mobile%20view%20-%20QR%20component.jpeg)

### Links
[Solution URL](https://github.com/m-ysabelb/QR-code-component-frontend-mentor-challenge)

[Live Site URL](https://m-ysabelb.github.io/QR-code-component-frontend-mentor-challenge/)

## My process
- # Plan and code your draft.
  As I first looked into the design, I presumed that it only takes a few divs in HTML, so I proceeded with planning, drafting, and coding simultaneously directly into the software environment.
  
- # Style the components.
  After creating the structure in HTML, I proceeded with styling the components as asked. This involves the background color, margins, font size, and alignments—all of which are not so new to me. The few struggling parts for me were the display and placing content, where you put the card at the utmost center of the viewing device. Similarly, doing it in a mobile-responsive manner was a bit of a challenge, yet thankfully, I still managed to complete the styles.

- # Test and try it for several times.
  Completing the whole code does not necessarily mean that your work is done. You need to look at it for several times, search for its flaws, and compare your output code if it already looks vastly similar to the given design. Your keen observation and attention to detail will be trained in this part. Also, your critical skills on how to solve the identified areas for improvement.

- # Release program.
  For the meantime, I did the mentioned steps before uploading my solution online. Hopefully, in my future projects, I'll be comfortable using Git for updating my GitHub repo, especially if I'm working on more challenging projects than this one.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Mobile-first Responsive Design
- VS Code Studio Software
- Github (gh-pages) for deployment

### Code Snippet Takeaways
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!--declared in the HTML head to display properly based on user's device -->

<link rel="stylesheet" href="style.css">
<!-- I can't believe I forgot this syntax during the process. I only realized that when my initialization in CSS does not work -->

<!-- not so sure about this but when I placed my img element inside div tags with class names, its CSS styles do not take effect. So my img was not inserted into divs, instead. -->
```

```css
/*start iniitialization*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/*margins shorthand property */
  element {
    margin: top right bottom left; 
  }

/*snippet in the actual code*/
  #heading {
    margin: 20px 5px auto 5px;
  }

  #text {
    margin: auto 20px 25px 20px;
  }

/*syntax for mobile responsive design*/
@media (max-width: 520px) /*the following code will take effect if width is 520px and below*/
{
  element {
    property: value;
  }
}

/*snippet in the actual code

the properties stated were needed to keep the card at the center and maintain the margins at the sides despite of the device's narrow viewport*/
@media (max-width: 380px) {
    .card {
        display: block;
        width: 90%;
        max-width: 350px;
        margin: 75px auto;
    }
}
```

### Continued development
These are the things that I want to work on in future projects:

- Anticipate project estimation
- Get used with CSS Styling and Properties
- Mobile-first responsive design
- Writing documentation for a completed project

### References
- [Fonts](fonts.google.com)
- [HSL to HEX](https://htmlcolors.com/hsl-to-hex)
- [Center element in a mobile responsive version](https://teamtreehouse.com/community/how-can-i-center-logo-with-css-mobile-responsive-version)

## Author
- GitHub - [@m-ysabelb](https://github.com/m-ysabelb)
- Frontend Mentor - [@m-ysabelb](https://www.frontendmentor.io/profile/m-ysabelb)

## Acknowledgment
Special thanks to Google for assisting newbie developers with the things they don't know yet.