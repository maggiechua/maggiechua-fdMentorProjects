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

## Overview

### Screenshot

![My Project](./qrCodeSS.png)

### Links

- Solution URL: [https://maggiechua.github.io/maggiechua-fdMentorProjects/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

While I have done some HTML/CSS in the past, I wouldn't say I felt particularly confident about my skills or understanding of frontend concepts. I think my previous foray was quite shallow as I knew how to apply the context, but I was missing the bigger picture on how to format elements, especially as the amount of items you need to include grow. 

```html
<h1>Some HTML code I'm proud of:</h1>
<div class="container">
    <img src="qrCode/images/image-qr-code.png" alt="a QR code pattern to visit the Frontend Mentor site">
    <h3 class="text">Improve your front-end skills by building projects</h3>
    <p class="text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
<div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://github.com/maggiechua" target="_blank">Maggie Chua</a>.
</div>
```
For instance, I didn't know about <div> and how you could use it to separate/group elements, which if done well, makes it a lot easier to style them later down the line. (I know it's basically all my index.html code, but it felt necessary to paste it to get my point across haha).

As a result, I think the way I structured my HTML made it easier to select items to style individually or collectively. While I still have a long way to go with understanding layouts, I have somewhat of an understanding on how to use flexbox as well as how to organize elements within it. As such, I feel especially proud of the .container code I did. I do admit that there's probably a way to simplify this, but I think it's quite good for my first try. 

```css
.container {
    position: absolute;
    height: 525px;
    width: 350px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    align-self: center;
    align-content: flex-start;
    align-items: center;
    box-sizing: border-box;
    border-radius: 15px;
    background-color: white;
}
```
Overall, I think the biggest thing I took away was that frontend is more interesting and fun than I had originally thought. Since I don't have a lot of experience working on such projects, it was a pretty fun first project and I think I learned a fair bit. 

### Continued development
#### v1
I think that for future projects, I still need to work on understanding layout properties, especially when to use flexbox vs grid as well as implementing the many functionalities that are offered by CSS. 

One thing I wasn't able to figure out was how to center the entire object in the center of the screen, both horizontally and vertically. So for the future, I definitely want to build my understanding on formatting objects on different levels within an HTML DOM, especially when nested within layouts. I also want to improve my understanding of positioning and when it would make sense to use absolute vs relative vs sticky, etc. I also realized upon observation, that it doesn't exactly format well on mobile or full-screen on desktop, since I was primarily copying it split screen TT. So, unfortunately, I will probably need to keep playing around with it.  

I plan to keep going through web.dev's HTML/CSS articles as well as working on other frontendmentor projects along the way after I finalize this one. 

#### v2
So, I decided to look at this again and I realized that I had to fix the positioning. I still don't quite understand how to decide what would be the best way to set units for a project, so I ended up defaulting to the 'simplest', albeit not as effective option. I realized that I should use a relative position for the parent and an absolute for the qrCode container as it would allow for it to be centered based on the positioning of its parent. I also used a flexbox for the items. Then, I used margins to push the text to right under the container (couldn't figure out how to do it without brute forcing it, but I think with future projects, I'll have to really dive into the documentation to find more effective ways of handling things).

The strange thing is that my github deployed page of this project doesn't show the image even though when I use the LiveServer option through VSCode it displays the project, just fine? 

### Useful resources
I primarily relied on the web.dev articles and all the resources they linked in there, so putting them here would be redundant. But definitely, found the articles on layouts, flexbox, margins, quite useful. 

## Author
- Github - [Maggie Chua](https://github.com/maggiechua)

