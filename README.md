# Ex08 Event Registration Web Application
## Date:24.12.2025

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
Page 1:
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="sec-logo-as" src="img/sec-logo-01as-2.png" />
      <img class="img" src="img/sec-logo-01as-3.png" />
      <img class="saveetha-logo" src="img/saveetha-logo-2.png" />
      <div class="text-wrapper">CULTURAL DAY EVENT</div>
      <div class="rectangle"></div>
      <div class="div">LOGIN</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="text-on-a-path-2" src="img/image.svg" />
      <img class="rectangle-2" src="img/rectangle-2.svg" />
      <div class="text-wrapper-2">REGISTER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">CULTURAL DAY EVENT</div>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 736px;
  min-height: 1002px;
  position: relative;
}

.iphone .sec-logo {
  position: absolute;
  top: 12px;
  left: 57px;
  width: 577px;
  height: 103px;
  aspect-ratio: 5.6;
}

.iphone .sec-logo-as {
  position: absolute;
  top: 0;
  left: 57px;
  width: 448px;
  height: 12px;
  aspect-ratio: 5.6;
}

.iphone .img {
  position: absolute;
  top: 17px;
  left: 94px;
  width: 573px;
  height: 115px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone .saveetha-logo {
  position: absolute;
  top: 132px;
  left: 261px;
  width: 201px;
  height: 193px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 352px;
  left: 73px;
  width: 586px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  position: absolute;
  top: 511px;
  left: 198px;
  width: 295px;
  height: 77px;
  background-color: #0000ff;
}

.iphone .div {
  position: absolute;
  top: 533px;
  left: 281px;
  width: 239px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 881px;
  left: 469px;
  width: 295px;
  height: 80px;
}

.iphone .text-on-a-path-2 {
  position: absolute;
  top: 870px;
  left: 469px;
  width: 295px;
  height: 76px;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 651px;
  left: 198px;
  width: 295px;
  height: 78px;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 666px;
  left: 248px;
  width: 247px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 352px;
  left: 73px;
  width: 572px;
  height: 94px;
  background-color: #ff0d0d;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 373px;
  left: 93px;
  width: 701px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

Page 2:
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <div class="text-wrapper">SPORTS EVENTS</div>
      <img class="line" src="img/line-1.svg" />
      <div class="frame"><div class="div">Football</div></div>
      <div class="div-wrapper"><div class="text-wrapper-2">Cricket</div></div>
      <div class="frame-2"><div class="text-wrapper-3">Volley ball</div></div>
      <div class="frame-3"><div class="text-wrapper-4">Throw ball</div></div>
      <img class="image" src="img/image-1.png" />
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 736px;
  min-height: 1002px;
  display: flex;
  flex-direction: column;
}

.iphone .saveetha-logo {
  margin-left: 292px;
  width: 152px;
  height: 146px;
  margin-top: 23px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .text-wrapper {
  margin-left: 187px;
  width: 334px;
  height: 48px;
  margin-top: 73px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .line {
  margin-left: 187.0px;
  width: 359.01px;
  height: 4px;
  margin-top: 9.0px;
  object-fit: cover;
}

.iphone .frame {
  margin-top: 60px;
  background-color: #2ca619;
  margin-left: 172px;
  width: 446px;
  height: 66px;
  display: flex;
  overflow: hidden;
}

.iphone .div {
  margin-top: 15px;
  width: 405px;
  height: 35px;
  margin-left: 127px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .div-wrapper {
  margin-top: 60px;
  background-color: #f60000;
  margin-left: 172px;
  width: 446px;
  height: 66px;
  display: flex;
  overflow: hidden;
}

.iphone .text-wrapper-2 {
  margin-top: 14px;
  width: 413px;
  height: 38px;
  margin-left: 140px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-2 {
  margin-top: 72px;
  background-color: #3ab9d2;
  margin-left: 172px;
  width: 446px;
  height: 66px;
  display: flex;
  overflow: hidden;
}

.iphone .text-wrapper-3 {
  margin-top: 9px;
  width: 389px;
  height: 48px;
  margin-left: 112px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-3 {
  margin-top: 54px;
  background-color: #ff00b2;
  margin-left: 172px;
  width: 446px;
  height: 66px;
  display: flex;
  overflow: hidden;
}

.iphone .text-wrapper-4 {
  margin-top: 10px;
  width: 416px;
  height: 45px;
  margin-left: 113px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .image {
  margin-left: 183px;
  width: 424px;
  height: 160px;
  margin-top: 23px;
  aspect-ratio: 2.65;
  object-fit: cover;
}

Page 3:
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <div class="frame"></div>
      <div class="auto-expo-wrapper">
        <p class="auto-expo"><span class="text-wrapper">Auto</span> <span class="span"> Expo</span></p>
      </div>
      <div class="div-wrapper"><div class="div">Dancing</div></div>
      <div class="frame-2"><div class="text-wrapper-2">Singing</div></div>
      <div class="frame-3"><div class="text-wrapper-3">DJ Party</div></div>
      <div class="frame-4"><div class="text-wrapper-4">Celebrities Attend</div></div>
      <div class="text-wrapper-5">EVENTS HELD</div>
      <img class="line" src="img/line-1.svg" />
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 736px;
  min-height: 1002px;
  position: relative;
}

.iphone .saveetha-logo {
  position: absolute;
  top: 5px;
  left: 292px;
  width: 152px;
  height: 146px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .frame {
  position: absolute;
  top: 238px;
  left: 78px;
  width: 426px;
  height: 47px;
}

.iphone .auto-expo-wrapper {
  position: absolute;
  top: 252px;
  left: 137px;
  width: 446px;
  height: 66px;
  display: flex;
  background-color: #fe1115;
  overflow: hidden;
}

.iphone .auto-expo {
  margin-top: 7px;
  width: 410px;
  height: 35px;
  margin-left: 116px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper {
  font-weight: 600;
}

.iphone .span {
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
}

.iphone .div-wrapper {
  position: absolute;
  top: 407px;
  left: 137px;
  width: 446px;
  height: 66px;
  display: flex;
  background-color: #14dfff;
  overflow: hidden;
}

.iphone .div {
  margin-top: 9px;
  width: 423px;
  height: 48px;
  margin-left: 133px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-2 {
  position: absolute;
  top: 567px;
  left: 137px;
  width: 446px;
  height: 66px;
  display: flex;
  background-color: #e6db07;
  overflow: hidden;
}

.iphone .text-wrapper-2 {
  margin-top: 11px;
  width: 414px;
  height: 43px;
  margin-left: 137px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-3 {
  position: absolute;
  top: 727px;
  left: 137px;
  width: 446px;
  height: 66px;
  display: flex;
  background-color: #2310f4;
  overflow: hidden;
}

.iphone .text-wrapper-3 {
  margin-top: 13px;
  width: 413px;
  height: 39px;
  margin-left: 135px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #0a0000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-4 {
  position: absolute;
  top: 887px;
  left: 137px;
  width: 446px;
  height: 66px;
  display: flex;
  background-color: #fe1115;
  overflow: hidden;
}

.iphone .text-wrapper-4 {
  margin-top: 13px;
  width: 420px;
  height: 40px;
  margin-left: 38px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 175px;
  left: 227px;
  width: 400px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .line {
  position: absolute;
  top: 227px;
  left: 186px;
  width: 339px;
  height: 5px;
  object-fit: cover;
}

Page 4:
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <div class="frame"><div class="text-wrapper">UPCOMING CELEBRITIES</div></div>
      <img class="image" src="img/image-1.png" />
      <div class="div">
        <div class="text-wrapper-2">DAY-1</div>
        <div class="text-wrapper-3">“Samantha”</div>
      </div>
      <div class="div">
        <div class="text-wrapper-2">DAY-1</div>
        <div class="text-wrapper-3">“Samantha”</div>
      </div>
      <div class="frame-2">
        <div class="text-wrapper-2">DAY-1</div>
        <div class="text-wrapper-3">“Samantha”</div>
      </div>
      <img class="img" src="img/image-2.png" />
      <div class="frame-3">
        <div class="text-wrapper-2">DAY-2</div>
        <div class="text-wrapper-4">“Vijay”</div>
      </div>
      <img class="image-2" src="img/image-3.png" />
      <div class="frame-4">
        <div class="text-wrapper-2">DAY-3</div>
        <div class="text-wrapper-4">“Anirudh”</div>
      </div>
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 736px;
  min-height: 1002px;
  position: relative;
}

.iphone .saveetha-logo {
  position: absolute;
  top: 17px;
  left: 292px;
  width: 152px;
  height: 146px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .frame {
  top: 211px;
  left: 87px;
  width: 561px;
  height: 98px;
  position: absolute;
  display: flex;
  background-color: #ffc0cb;
  overflow: hidden;
}

.iphone .text-wrapper {
  margin-top: 24px;
  width: 542px;
  height: 74px;
  margin-left: 34px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .image {
  top: 386px;
  left: 11px;
  width: 270px;
  height: 151px;
  aspect-ratio: 1.79;
  position: absolute;
  object-fit: cover;
}

.iphone .div {
  position: absolute;
  top: 383px;
  left: 326px;
  width: 366px;
  height: 123px;
  display: flex;
  flex-direction: column;
  gap: 11px;
  background-color: #ffc0cb;
  overflow: hidden;
}

.iphone .text-wrapper-2 {
  margin-left: 102px;
  width: 322px;
  height: 51px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  margin-left: 61px;
  width: 314px;
  height: 22px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .frame-2 {
  top: 378px;
  left: 326px;
  width: 366px;
  height: 123px;
  flex-direction: column;
  gap: 11px;
  position: absolute;
  display: flex;
  background-color: #ffc0cb;
  overflow: hidden;
}

.iphone .img {
  top: 568px;
  left: 55px;
  width: 181px;
  height: 263px;
  aspect-ratio: 0.69;
  position: absolute;
  object-fit: cover;
}

.iphone .frame-3 {
  top: 616px;
  left: 326px;
  width: 366px;
  height: 123px;
  flex-direction: column;
  gap: 11px;
  position: absolute;
  display: flex;
  background-color: #ffc0cb;
  overflow: hidden;
}

.iphone .text-wrapper-4 {
  margin-left: 102px;
  width: 314px;
  height: 22px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .image-2 {
  top: 857px;
  left: 77px;
  width: 137px;
  height: 137px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.iphone .frame-4 {
  top: 842px;
  left: 302px;
  width: 366px;
  height: 123px;
  flex-direction: column;
  gap: 11px;
  position: absolute;
  display: flex;
  background-color: #ffc0cb;
  overflow: hidden;
}

```

## OUTPUT:
![alt text](<Screenshot (16).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
