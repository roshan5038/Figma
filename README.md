# Ex09 Event Registration Web Application
## Date:19/12/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
page 1 HTML Code

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="istockphoto" src="img/istockphoto-601938956-612x612-1.png" />
      <img class="SEC-LOGO" src="img/SEC-LOGO-2.png" />
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="div">CULTURALS EVENTS</div>
    </div>
  </body>
</html>

page 1 CSS Code

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 366px;
  min-height: 793px;
  position: relative;
}

.iphone .istockphoto {
  position: absolute;
  top: 0;
  left: 0;
  width: 366px;
  height: 793px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

.iphone .SEC-LOGO {
  position: absolute;
  top: 34px;
  left: 0;
  width: 362px;
  height: 97px;
  aspect-ratio: 3.75;
  object-fit: cover;
}

.iphone .SEC-logo {
  position: absolute;
  top: 160px;
  left: 73px;
  width: 220px;
  height: 212px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 431px;
  left: 79px;
  width: 214px;
  height: 67px;
  background-color: #22577a;
}

.iphone .text-wrapper {
  position: absolute;
  top: 442px;
  left: 114px;
  width: 177px;
  font-family: "Jockey One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 704px;
  left: 697px;
  width: 184px;
  height: 30px;
}

.iphone .div {
  position: absolute;
  top: 385px;
  left: 117px;
  width: 206px;
  font-family: "Julius Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #82d1e3;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}
 

page 2 HTML Code

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="istockphoto" src="img/istockphoto-601938956-612x612-2.png" />
      <p class="CULTURALS-DAY-EVENTS">
        <span class="text-wrapper">CULTURALS DAY EVENTS</span> <span class="span"></span>
      </p>
      <div class="MUSIC-RAMPWALK-JUST">
        MUSIC<br /><br />RAMPWALK<br /><br />JUST A MINUTE (JAM)<br /><br />DANCE<br /><br />SHIPWRECK<br /><br />ADAPTUNE
      </div>
    </div>
  </body>
</html>

page 2 CSS Code 

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 366px;
  min-height: 793px;
  position: relative;
}

.iphone .istockphoto {
  position: absolute;
  top: 0;
  left: 0;
  width: 366px;
  height: 793px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

.iphone .CULTURALS-DAY-EVENTS {
  position: absolute;
  top: 75px;
  left: 41px;
  width: 315px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper {
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
}

.iphone .span {
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
}

.iphone .MUSIC-RAMPWALK-JUST {
  position: absolute;
  top: 175px;
  left: 48px;
  width: 265px;
  font-family: "Julius Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

page 3 HTML Code

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="istockphoto" src="img/istockphoto-601938956-612x612-3.png" /></div>
  </body>
</html>

page 3 CSS Code

.image {
  width: 1056px;
  height: 792px;
}

.image .istockphoto {
  position: fixed;
  top: 0;
  left: 345px;
  width: 366px;
  height: 792px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

page 4 HTML Code

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="SEC-LOGO" src="img/SEC-LOGO-2-1.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="WE-ARE-EAGERLY">
        WE ARE EAGERLY WAITING FOR YOUR PARTICIPATION !<br />ALL THE VERY BEST FOR YOUR PERFORMANCE
      </p>
      <p class="FOR-QUERIES-CONTACT">
        <span class="span">FOR QUERIES<br /></span>
        <span class="text-wrapper-2">CONTACT US <br /></span>
        <span class="span">saveethaengineeringcollege.com/events</span>
      </p>
    </div>
  </body>
</html>

page 4 CSS Code

.iphone {
  background-color: #27213c;
  width: 100%;
  min-width: 366px;
  min-height: 793px;
  position: relative;
}

.iphone .SEC-LOGO {
  position: absolute;
  top: 0;
  left: 0;
  width: 347px;
  height: 93px;
  aspect-ratio: 3.75;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 242px;
  left: 57px;
  width: 289px;
  font-family: "Junge-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .WE-ARE-EAGERLY {
  position: absolute;
  top: 356px;
  left: 57px;
  width: 257px;
  font-family: "Junge-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .FOR-QUERIES-CONTACT {
  position: absolute;
  top: 555px;
  left: 60px;
  width: 230px;
  transform: rotate(-0.22deg);
  font-family: "Junge-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .span {
  color: #ffffff;
}

.iphone .text-wrapper-2 {
  color: #f0cb13;
}



```


## OUTPUT:
![alt text](<page 1.png>)

![alt text](<page 2.png>)

![alt text](<page 3.png>)

![alt text](<page 4.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
