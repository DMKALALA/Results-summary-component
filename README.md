# Results-summary-component


This is a solution to the [Results-summary-component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV/hub). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./assets/images/Screenshot%20from%202023-05-02%2008-58-49.png)



### Links

- Solution URL: (https://github.com/DMKALALA/Results-summary-component)
- Live Site URL: (https://dmkalala.github.io/Front_end_mentor_html_css/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used.
Always open to any comments


```css


body{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    min-height: 100vh;
    gap: 20px;
    font-family: "Hanken Grotesk", sans-serif;
    /*This is a link to a CSS stylesheet that is hosted on the Google Fonts server. It is specifying the font family "Hanken Grotesk" with three different font weights: 500, 700, and 800. The "display" property is set to "swap", which means that the font will be loaded asynchronously and swapped in as soon as it becomes available. This can help improve the performance of the page. */
    
}

.content{
    display: flex;
    width: 600px;
    justify-content: center;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0px 3px 8px  rgb(0, 0, 0, 0.24);
}

.left-container{
    color: hsl(0, 0%, 100%);
    box-shadow: inset 1px 1px 12px 0px hsla(256, 72%, 46%, 1);
    padding: 20px;
    width: 50%;
    border-radius: 20px;
    background: linear-gradient(hsl(252, 100%, 67%),hsl(241, 81%, 54%));
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.right-container{
    width: 50%;
    padding: 20px;
}

.score-box{
    padding: 50px;
    width: 70px;
    height: 70px;
    border-radius: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    background: linear-gradient(hsla(256, 72%, 46%, 1),hsla(241, 72%, 46%, 0));
    
}

.big-score{
    
    color: hsl(0, 0%, 100%);
    font-weight: bold;
    font-size: 60px;
}

.score-con{
    display: flex;
    

}

.Reaction{
    display: flex;
    justify-content: space-between;
    background-color: hsl(0, 100%, 67%, 0.1);
    color: hsl(0, 100%, 67%);
    margin-bottom: 10px;
    padding: 15px;
    border-radius: 10px;
}

.Memory{
    display: flex;
    justify-content: space-between;
    background-color: hsl(39, 100%, 56%, 0.1);
    color: hsl(39, 100%, 56%);
    margin-bottom: 10px;
    padding: 15px;
    border-radius: 10px;
}

.Verbal{
    display: flex;
    justify-content: space-between;
    background-color: hsl(166, 100%, 37%, 0.1);
    color: hsl(166, 100%, 37%);
    margin-bottom: 10px;
    padding: 15px;
    border-radius: 10px;
}

.Visual{
    display: flex;
    justify-content: space-between;
    background-color: hsl(234, 85%, 45%, 0.1);
    color: hsl(234, 85%, 45%);
    padding: 15px;
    border-radius: 10px;

}

.Continue{
  margin-top: 30px;
  padding: 15px 30px;
  border: none;
  color: white;
  outline: none;
  background-color: hsl(224, 30%, 27%);
  width: 100%;
  border-radius: 20px;
}




.grey-text {
    color: rgba(87, 87, 87, 0.992);
}

.black-text {
    color: hsl(0, 0%, 13%);
    font-weight: bold;
}

.text{
    font-size: 18px;
}

.Continue:hover{
    background: linear-gradient(hsl(241, 82%, 52%),hsla(194, 70%, 49%, 0.4));
    color: hsl(0, 0%, 0%);
}

@media screen and (max-width:600px) {
    body {
        align-items: flex-start;
        background-color: white;
      }
      .content{
        box-shadow: none;
      }
      .content {
        flex-direction: column;
      }
      .left-container {
        border-radius: 20px;
        width: 100%;
      }
      .left-container .text{
        width: 250px;
      }
      .right-container{
        border-radius: 20px;
        width: 100%;
      }

      .text{
        display: flex;
        align-self: center;
      }

}

/*This is a CSS media query that applies styles to the webpage when the screen width is less than or equal to 600 pixels.*/
```

### Continued development

I would like to make my own QR Generator so this could be used as a default template.

The qr code could be links to a document or something along those ways. Going to think about something useful that could come in handy.

### Useful resources

- [FLEXBOX FROGGY](https://flexboxfroggy.com/#es) - This helped me to understand better how to use flexbox.


## Author

- Frontend Mentor - [@DMKALALA](https://www.frontendmentor.io/profile/DMKALALA)

## Acknowledgments


At some point i was a little stuck with setting the style for the image. And i found this video helpful.

(https://www.youtube.com/watch?v=Hd3QVIwul3s&t=42s)
