# FoodSavor Named Project for learning SCSS

The design is taken from [Jetsetter Figma Design Link](https://www.figma.com/community/file/1075546859187487919) Thanks to him for this design.


## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [My Social Links](#my-social-links)


## Overview

This a practice project for learning scss. 

### Screenshot

![Design](https://raw.githubusercontent.com/wagaskon/FoodSavor_HTMLSCSS/master/images/Design.png?token=GHSAT0AAAAAAB5QD2URS7N3RT4LVUEQLVAMY6325XQ)

### Links

- Solution URL: [Codepin](https://codepen.io/wagaskon/pen/MWBZeeR)
- Live Site URL: [Deployed on Netlify](https://master--fluffy-treacle-4fb6d1.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Scaled CSS (using rem)
- SCSS


### What I learned

In this project I learned many things like flexbox, SCSS instead of Custom CSS and in SCSS I learned nesting, variables, importing fonts, varibles storing many styles etc. I also tried to keep the design in Semantic HTML.
The purpose of this project was to get back into the programming after my gap in practice.

The over structure (overview) of the HTML is as follows:

```html
<body>
    <header class="header">
        <div class="icon">
        </div>
        <nav>
        </nav>
        <button class="btn">Sign Up</button>
    </header>
    <main>
        <div class="main_content">
            <div class="portion_main">                
                <button> Get started </button>
                <div class="Customers">    
                </div>
            </div>
            <div class="front_images">
            </div>
        </div>
    </main>

    <section class="section_1 quest_text">
        </div>
        <div class="sub_section1">            
        </div>
    </section>
    <section class="section_2 quest_text">
        <div class="Declaration1">
        </div>
        <div class="Feed_Sub">
            <div class="dev">  </div>
            <div class="dev"> </div>

            </div>
            <div class="dev"> </div>
            </div>
        </div>
    </section>
    <footer class="footer">
    </footer>
```
Some of the SCSS properties I really liked are:

```scss
%flex{
    display: flex;
}
%flex1{
    display: flex;
    justify-content: center;
}
%flex2{
    display: flex;
    justify-content: center; 
    align-items: center;
}
%textfont{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 700;
    font-size: 3rem;
}
$Whitecolor: #FFFFFF;
$GreenColor: #7EB685;
$GreenColor2:#DEEDE0;


%button{
    width: 25rem;
    height: 7rem;
    background-color: $GreenColor;
    border: none;;
    border-radius: 5rem;
    @extend %textfont;
    color: $Whitecolor;
}
```
I also learned how to use the @extend property in SCSS. It is very useful to extend the properties of a class to another class. 
### Continued development

- Media Queries can be added to make it responsive.
- Animations and Transitions can be added to make it more interactive.
- Multiple pages can be added to make it more interactive.

### Useful resources

- [W3School](https://www.w3schools.com/) - This resource is perfect for beginners. It has all the basic information about HTML, CSS, SCS, etc. It also has a lot of examples which are very helpful.
- [SCSS official Docs](https://sass-lang.com/guide) - official docs of SCSS. It has all the information about SCSS and how to use it.


## My Social Links

- Twitter - [Wagaskon](https://twitter.com/wagaskon)
- Dev.to - [Wagaskon](https://dev.to/waqaskhan)
- Codepen - [Wagaskon](https://codepen.io/wagaskon)
- Linkedin - [Wagaskon](https://www.linkedin.com/in/waqaskhandev/)
- Github - [Wagaskon](https://github.com/wagaskon)

