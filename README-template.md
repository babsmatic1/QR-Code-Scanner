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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./Screenshots/Qr-Code%20Desktop%20Image.png)
![](./Screenshots/Qr-Code%20Mobile%20Image.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- I started by gathering all necessary assets, such as images and designs, and placing them into their respective folders for easy access and proper file structure
- Next, I reset the default padding and margin to 0 for a clean slate and applied box-sizing: border-box; to all elements. This ensures that padding and borders are included within the element's width and height, simplifying layout calculations..
- I then focused on fixing the white container in the center of the viewport using CSS flexbox for both horizontal and vertical alignment, ensuring it stays responsive. 
- After that, I imported the image, resized it to match the design specifications, and positioned it correctly 
- It was smooth sailing from that point


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Chat-Gpt assistance (in understanding flexbox, not in copying code)
- Desktop-first workflow



### What I learned

A major thing i learnt is positioning and using the flex property, that was an eye opener. I thought i had understood positioning to a good point till i faced this challenge. Trying to put the box at the center of the view-port was initially more challenging than i'd like to admit, i had to step back to chat-gpt and had it explain positioning under different contexts to me then i picked the flexbox method as it was less tricky and more straightforward. The snippet below was the mastermind behind the positioning:


```css
html, body{
    background-color: #D5E1EF;
    height: 100%;
}

body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```


### Continued development

I want to get better at positioning elements properly. I successfully centralized the elements in this challenge but i think i would have faced a problem if there were other elements on the screen that didn't need to be centralized. 




## Author

- Website - [Destiny Job](https://www.thedestinyjob.com)
- Frontend Mentor - [@destinyjob](https://www.frontendmentor.io/profile/destinyjob)
- Twitter - [@thedestinyjob](https://x.com/theDestinyJob)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

