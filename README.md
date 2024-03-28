 # Travelopia

## Introduction
This repository contains a small assignment project created for Travelopia. The project is a static website built using HTML, CSS, and JavaScript. The Block Element Modifier (BEM) architecture was employed to structure and organize the CSS for a modular and maintainable codebase.

## Project Type
### Frontend

## Deployed App

***Client link*** 

[https://travelopia-assignment-tan.vercel.app](https://travelopia-assignment-tan.vercel.app)


## Directory Structure

travelopia_assignment/
├─ images/
├─index.css
├─ index.html
├─index.js
├─ README.md



## Features
- Navbar
- Display hero section
- Popup Box with Hello World!!
- Footer section

## Design 

![travelopia](https://github.com/khelsai01/travelopia_assignment/assets/119441119/5ad3f995-6f5c-4986-881e-569346703796)

## Responsiveness

***Medium screen***

![responsive1](https://github.com/khelsai01/travelopia_assignment/assets/119441119/409218d5-96de-49cb-af37-884c392372ad)

![responsive](https://github.com/khelsai01/travelopia_assignment/assets/119441119/992ea430-cd40-48e8-a55d-5ed7508a44e0)

***Mobile screen***

![mobile](https://github.com/khelsai01/travelopia_assignment/assets/119441119/3d628b19-e5fa-4d2f-becb-e7e1ea47f5c1)

### Navbar 

 ![navbar](https://github.com/khelsai01/travelopia_assignment/assets/119441119/30fcf68f-b5e6-40cc-b7b4-117899ca5fac)

    In the Navbar have two portion left corner have name of project, right side have some navigation components.
    - for Achieve this style by flex property for align the content in row
    - Height of the navebar is 100px according to given in problem.
    
![navbar humb](https://github.com/khelsai01/travelopia_assignment/assets/119441119/77787d0d-ebf4-4d53-9482-7b1319caa7d9)

    - One humburger icon have given from external icon library by using CDN link. And given the designing for large screen it's display none and for small screen Display block property use.
    - Navbar has been responsive for the all screen size. Achieve by media quary property of CSS.

### Image section

![hero](https://github.com/khelsai01/travelopia_assignment/assets/119441119/e4942200-8fa6-4449-b3c7-2b32cd383f29)


     In the hero section One image is taken at the middle of the header and footer section
     - Image is full-width, full-height, and fluied responsive
     - Achieve for responsive size of image is by  .image-container {height: calc(100vh - 200px);width: 100} and .image-container img {height: 100%;object-fit: cover;width: 100%}
     - Decide to take height in calc function, when the screen size change then the height is adjust according to the available height and also remove my 100px+100px of header and footer height.
     - Image width is 100% and object-fit:cover is taken, at the responsive size of screen the image is adjust the size and fit on cover.

     Overlay
     - Overlay section is given on over to image and then after the image is look some blur like .
     - Get the design by
    
    translucent-overlay {
    background-color: #53535390;
    width: 100%;
    height: 100%;
    position: absolute;
    left: 0;
    top: 0
    }
    
    When you apply position: absolute; to an element, it is taken out of the normal document flow, meaning it won't affect the position of other elements on the page. Instead, it will be placed based on the coordinates you specify using the top, bottom, left, and right properties.
    width and height is 100% on box.
    
 ![text](https://github.com/khelsai01/travelopia_assignment/assets/119441119/afb1c0ef-edcc-44c1-8a97-8f0641d812a1)

    Title over image is get by the
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    
    - This above property is give the section is center of the screen
    
    font-size: calc(0.5833333333vw + 10.6666666667px);
    text-transform: uppercase;
    text-align: center;
    
    - This property is help to center the text and text all charactor in uppercase.
    
![popup](https://github.com/khelsai01/travelopia_assignment/assets/119441119/3a9339b6-6137-4a68-b841-59741f2010d8)

    Cleck Me button 
    on click on Click Me button alert popup box appear on with the Hello World !! text .
    - By javascript and CSS Achieve this functionality

### footer section

    
   ![footer](https://github.com/khelsai01/travelopia_assignment/assets/119441119/cbe25f65-e22a-4e23-81b1-eab497e3879d)
   
    - In the footer section available deatils of travelopia copy rigth information 
    - Footer height is 100px and width is 100% of screen as per given problem.

 

## Installation & Getting started
Detailed instructions on how to install, configure, and get the project running. For Tasks Manager app projects, guide the reviewer how start the project local etc.

***For local***
```bash
. open CMD terminal
. git clone `https://github.com/khelsai01/travelopia_assignment.git`
. cd travelopia_assignment
. right click on index.html -> click on open with live server.
. opend at browser
```

```bash
travelopia hero secton with navbar and footer and popup alert box with Hello World.
```

## Landing page of task Manager

## Technology Stack

- HTML
- Cascading Style Sheets
- vanilla javascripts
- Github
- Vercel
