**Note: This is a README.md template file for you to use to describe the project you have completed. README's are used so that other developers can understand what your project is about. You will commonly see README's used on Github where they will be displayed on a project's repository. Delete this note after reading**

# BNTA - Shop landing page assessment day solution

This is a solution to the Shop landing page BNTA assessment day which will allow you to put the HTML and CSS you've learned in practice with a stretch goal of adding a Dark Mode to your site.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

**Your users should be able to:**

- Build your webpage correctly for viewing within a fullscreen desktop window using HTML & CSS

**Stretch goals:**

- Implement a Dark Mode button using HTML and JavaScript

The teaching from the first day of the assessment centre should put you in good stead for this project and what today aims to provide is a chance to put this learning into action.

### Screenshot

![](./design.websiteDoritos.jpeg)

Add a screenshot of your solution. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the sentences above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

## My process

Starting point:

First thing we did was to decide on what products we wanted to design our website around. 2 ideas were proposed - holiday destinations or gym equipment. As a team we voted on gym equipment.
We jumped straight onto excalidraw, which Ed kindly presented before, and started making our basic plan for our landing page.
A lot of our inspiration was from a current gym style webpage -> https://www.strengthshop.co.uk/

Once we were happy with our template we created our trello accounts and went on there to see the order of the tasks we should be taking and to tick off any admin tasks we had already completed.

Right before starting our LiveShare coding we made sure to split up the tasks evenly between the four; Sujan was responsible for the header+Navbar, Lewis and William were both working on the body as it took up majority of the web page, and Mohamed was responsible for the footer which would include icons.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript
- icons from "https://fontawesomeicons.com/svg/icons"

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Sujan - My biggest learning was made using the inspect element when trying to adjust the CSS the connected to my header HTML. The inspect element helped my understanding of flex display a lot. especially since I could pick out individual code using the cursor within the inspect element to see what is going on with individual elements. I also learned a lot from w3schools website where I used their code to make dropdown lists on the navbar. 

```html
<div class="ssdropdown">
                        <button class="ssdropbtn">Equipment</button>
                        <div class="ssdropdown-content">
                            <a href="#">Dumbbells</a>
                            <a href="#">Barbells</a>
                            <a href="#">Bumper Plates</a>
                            <a href="#">Resistance Bands</a>
                            <a href="#">Belts</a>
                        </div>
                    </div>
```                    
```css
.ssdropdown-content {
    display: none;
    position: absolute;
    background-color: white;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
}
```


Lewis - The most impactful thing I learned was the usage of <div> in order to style individual parts of my HTML code, such as colouring certain features, adding highlights upon interaction with the HTML objects (buttons) as well as the removal of text features. Using guidance from w3schools.com, I was able to add a slideshow which would transition images with the click of a button.


Mohamed - I have learned how to make a div section keep within the same line by using the inline attribute. I have also learned how to change the svg colour when hovering mouse over by using the path and fill attributes in css and that is the part I am most proud of in my code. Along with the other CSS attributes of the social media icons.

```CSS
.msicons:hover path{
    fill: red;
}
```

```CSS
.mssm {
    display: inline;
    margin: 1em;
    border: grey;
    padding-top: 1.5em;
    padding-left: 0.5em;
    padding-right: 0.5em;
    background-color: white;
    
}
```

Will - My biggest learning was how to get different formatting points interact with each other, for instance having an image also work as a hyperlink, and how to overlay text on an image so that it stayed with the image and scaled with the webpage. I needed to fiddle about with the nested and separate <div>s a lot to get this to work.

```html
div class ="wpictures">
                    <div>
                        <a href ="#">
                            <img src="https://source.unsplash.com/fqMu99l8sqo " width = "95%" height = "90%" alt="EQUIPMENT">
                            <div class="wbottom-left">EQUIPMENT</div>
                        </a>
                    </div>
                    <div>
                        <a href ="#"><img src="https://source.unsplash.com/20jX9b35r_M" width = "95%" height = "90%" alt="NEW IN">
                            <div class="wbottom-right">NEW IN</div>   
                        </a>
                    </div>

```

```css
.wpictures {
    max-width: 1500px;
    padding-top: 0;
    padding-bottom: 0;
    margin:auto;
    /* from w3schools on overlaying text on image*/
    position: relative;
    text-align: center;
    color: white;
    /* from blogpost on aligning images horizontally, put in separate divs*/
    display: flex;
    justify-content: space-between;
}

```

### Continued development



Will - I'dlike to explore more the use of different flexbox techinques to align elements differently

Mohamed - I have read about using animations in CSS but did not have time to learn and implement it for this project and would like to try experiment with CSS animations in future projects.

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources


The reasons we used and has helped us with completing our proects include;
- icons from "https://fontawesomeicons.com/svg/icons"
- flexbox tutorials from "https://flexboxfroggy.com/"
- code snippets from "https://www.w3schools.com/"

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Authors

- 4Musketeers - Sujan Sriram, Lewis McFarlane, William Dorling, Mohamed Shire

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Sujan - got help with changing the font style in the header and navbar. Really liked the font William and Lewis used in the body so I stole that piece of code to help bring the website more together. Also got help from Mohamed with adding an icon to my searchbar.


This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**