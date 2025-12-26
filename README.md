# Ex08 Event Registration Web Application
## Date:26-12-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
page 1

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="screenshot"><img class="img" src="img/screenshot-2025-12-26-104606-1.png" /></div>
      <div class="text-wrapper">welcomes you!</div>
      <p class="to-the-annual-sports">
        To the annual sports<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; meet
      </p>
      <div class="rectangle"></div>
      <div class="saveetha-engineering">
        Saveetha Engineering<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;College
      </div>
      <div class="div"></div>
      <div class="text-wrapper-2">25 th december 2025</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.iphone-pro-max {
  background-color: #dc1b1b;
  overflow: hidden;
  width: 100%;
  min-width: 516px;
  min-height: 750px;
  position: relative;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 0;
  left: -47px;
  width: 764px;
  height: 750px;
  display: flex;
  aspect-ratio: 1.02;
}

.iphone-pro-max .img {
  margin-left: 6.15%;
  width: 516px;
  margin-right: -6.15%;
  flex: 1;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 340px;
  left: 108px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .to-the-annual-sports {
  position: absolute;
  top: 441px;
  left: 60px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 186px;
  left: 29px;
  width: 453px;
  height: 121px;
  background-color: #e7ed7d;
}

.iphone-pro-max .saveetha-engineering {
  position: absolute;
  top: 211px;
  left: 43px;
  width: 429px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 585px;
  left: 17px;
  width: 477px;
  height: 103px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 611px;
  left: 60px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page 2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="screenshot" src="img/screenshot-2025-12-26-104606-2.png" />
      <div class="text-wrapper">Basketball,volleyball</div>
      <div class="div">baseball,cricket</div>
      <div class="text-wrapper-2">Events</div>
      <div class="text-wrapper-3">Football</div>
      <div class="rectangle"></div>
      <div class="venue-ground-sec">Venue:Ground,sec<br />backside</div>
      <div class="text-wrapper-4">Track and field</div>
      <div class="text-wrapper-5">Time:8am-5pm</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.iphone-pro-max {
  background-color: #eb1919;
  width: 100%;
  min-width: 516px;
  min-height: 750px;
  position: relative;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 516px;
  height: 750px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 327px;
  left: 42px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 388px;
  left: 42px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 191px;
  left: 42px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 268px;
  left: 42px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 599px;
  left: 42px;
  width: 438px;
  height: 110px;
  background-color: #6e15db;
}

.iphone-pro-max .venue-ground-sec {
  position: absolute;
  top: 606px;
  left: 54px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 465px;
  left: 42px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 533px;
  left: 109px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

page 3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="screenshot" src="img/screenshot-2025-12-26-104606-3.png" />
      <p class="registration-free">
        <span class="text-wrapper">Registration</span>
        <span class="span">: </span>
        <span class="text-wrapper-2">Free for<br /></span>
        <span class="text-wrapper-3">SEC</span>
        <span class="text-wrapper-4">&nbsp;</span>
        <span class="text-wrapper-2">students.Others use <br />the link </span>
        <span class="text-wrapper-5">www.sec.com<br /></span>
        <span class="text-wrapper-2">to register!</span>
      </p>
      <div class="rectangle"></div>
      <div class="div">REGISTER NOW!</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-6">Limited seats</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-7">Hurry!!</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 515px;
  min-height: 750px;
  position: relative;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 515px;
  height: 750px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

.iphone-pro-max .registration-free {
  position: absolute;
  top: 174px;
  left: 43px;
  width: 430px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper {
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #000000;
}

.iphone-pro-max .span {
  font-weight: 800;
  color: #000000;
}

.iphone-pro-max .text-wrapper-2 {
  font-family: "Inter-Italic", Helvetica;
  font-style: italic;
  color: #000000;
}

.iphone-pro-max .text-wrapper-3 {
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #4714d3;
}

.iphone-pro-max .text-wrapper-4 {
  font-family: "Inter-Italic", Helvetica;
  font-style: italic;
  color: #4714d3;
}

.iphone-pro-max .text-wrapper-5 {
  font-family: "Inter-Italic", Helvetica;
  font-style: italic;
  color: #100ce8;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 612px;
  left: 50px;
  width: 424px;
  height: 100px;
  background-color: #13e60c;
}

.iphone-pro-max .div {
  position: absolute;
  top: 640px;
  left: 111px;
  width: 294px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 384px;
  left: 61px;
  width: 393px;
  height: 95px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 402px;
  left: 111px;
  width: 426px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 506px;
  left: 89px;
  width: 300px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 522px;
  left: 161px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

```

## OUTPUT:

![alt text](<Screenshot (30).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
