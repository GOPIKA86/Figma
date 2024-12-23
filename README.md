# Ex09 Event Registration Web Application
## Date:23/12/2024

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
Home Page
HTML
<div class="container--0-">
<div class="text-0-1-2">DANCE EVENT</div>
  <svg
    width="234"
    height="66"
    viewBox="0 0 234 66"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="234" height="66" fill="#A726F2"></rect>
  </svg>
  <div class="text-0-1-4">LOGIN</div>
  <svg
    width="236"
    height="63"
    viewBox="0 0 236 63"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="236" height="63" fill="#A726F2"></rect>
  </svg>
  <div class="text-0-1-6">REGISTER</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: -220px;
  top: -502px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 297.5357666015625px;
  height: 37.01531982421875px;
  color: #d4c81b;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 145px;
  height: 48px;
  color: #4d0a56;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 191px;
  height: 48px;
  color: #4d0a56fc;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}

EVENT
HTML

<div class="container--0-">
<div class="text-0-1-1">DANCE EVENTS</div>
  <svg
    width="45"
    height="48"
    viewBox="0 0 45 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M22.5 0L27.7761 17.9656H44.8498L31.0369 29.0689L36.313 47.0344L22.5 35.9311L8.68705 47.0344L13.9631 29.0689L0.150171 17.9656H17.2239L22.5 0Z"
      fill="#D9D9D9"
    ></path>
  </svg>
  <div class="text-0-1-3">Rhythm &#x26; Moves</div>
  <svg
    width="49"
    height="53"
    viewBox="0 0 49 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M24.5 0L30.2251 20.0385L48.7519 20.0385L33.7634 32.423L39.4885 52.4615L24.5 40.077L9.51148 52.4615L15.2366 32.423L0.248058 20.0385L18.7749 20.0385L24.5 0Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="49"
    height="53"
    viewBox="0 0 49 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M24.5 0L30.2251 20.0385L48.7519 20.0385L33.7634 32.423L39.4885 52.4615L24.5 40.077L9.51148 52.4615L15.2366 32.423L0.248058 20.0385L18.7749 20.0385L24.5 0Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="49"
    height="50"
    viewBox="0 0 49 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M24.5 0L30.2251 19.002H48.7519L33.7634 30.7459L39.4885 49.748L24.5 38.0041L9.51148 49.748L15.2366 30.7459L0.248058 19.002H18.7749L24.5 0Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="56"
    height="51"
    viewBox="0 0 56 51"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M28 0L34.5109 19.3475H55.5806L38.5349 31.305L45.0458 50.6525L28 38.695L10.9542 50.6525L17.4651 31.305L0.419361 19.3475H21.4891L28 0Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="50"
    height="55"
    viewBox="0 0 50 55"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M25 0L30.8374 20.7295H49.7275L34.4451 33.541L40.2824 54.2705L25 41.459L9.71758 54.2705L15.5549 33.541L0.272532 20.7295H19.1626L25 0Z"
      fill="#D9D9D9"
    ></path>
  </svg>
  <div class="text-0-1-9">The Rhythm Fest</div>
  <div class="text-0-1-10">Jazz Jive Jam</div>
  <div class="text-0-1-11">Rhythm Rivals</div>
  <svg
    width="53"
    height="51"
    viewBox="0 0 53 51"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M26.5 0L32.6741 19.3475H52.6541L36.49 31.305L42.6641 50.6525L26.5 38.695L10.3359 50.6525L16.51 31.305L0.345945 19.3475H20.3259L26.5 0Z"
      fill="#D9D9D9"
    ></path>
  </svg>
  <div class="text-0-1-13">Step Up Night</div>
  <div class="text-0-1-14">Dance Dynasty</div>
  <div class="text-0-1-15">Disco Fever Night</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 317px;
  top: -469px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 305px;
  height: 48px;
  color: #17115d;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 317px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 320px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 266px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 265px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 267px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 287px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-15 {
  width: 335px;
  height: 48px;
  color: #ffffff;
  font-size: 40px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}

REGISTER
HTML
<div class="container--0-">
<svg
    width="277"
    height="81"
    viewBox="0 0 277 81"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="277" height="81" fill="#B2A713"></rect></svg
  ><svg
    width="331"
    height="50"
    viewBox="0 0 331 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="331" height="50" fill="#D9D9D9"></rect></svg
  ><svg
    width="305"
    height="49"
    viewBox="0 0 305 49"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="305" height="49" fill="#D9D9D9"></rect></svg
  ><svg
    width="295"
    height="55"
    viewBox="0 0 295 55"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="295" height="55" fill="#D9D9D9"></rect></svg
  ><svg
    width="292"
    height="50"
    viewBox="0 0 292 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="292" height="50" fill="#D9D9D9"></rect></svg
  ><svg
    width="333"
    height="56"
    viewBox="0 0 333 56"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="333" height="56" fill="#D9D9D9"></rect></svg
  ><svg
    width="266"
    height="50"
    viewBox="0 0 266 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="266" height="50" fill="#D9D9D9"></rect></svg
  ><svg
    width="266"
    height="50"
    viewBox="0 0 266 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="266" height="50" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-9">EVENT REGISTRATION FORM</div>
  <div class="text-0-1-10">Fill the form</div>
  <svg
    width="304"
    height="53"
    viewBox="0 0 304 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect
      x="304"
      y="53"
      width="304"
      height="53"
      transform="rotate(180 304 53)"
      fill="#D9D9D9"
    ></rect>
  </svg>
  <div class="text-0-1-12">Full Name</div>
  <div class="text-0-1-13">Gender</div>
  <div class="text-0-1-14">Age</div>
  <div class="text-0-1-15">Register Number</div>
  <div class="text-0-1-16">Department</div>
  <div class="text-0-1-17">Mobile Number</div>
  <div class="text-0-1-18">Email ID</div>
  <div class="text-0-1-19">Event To Register</div>
  <div class="text-0-1-20">REGISTER</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 840px;
  top: -480px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-9 {
  width: 440px;
  height: 38px;
  color: #0dff2a;
  font-size: 24px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 204px;
  height: 24px;
  color: #56e8ff;
  font-size: 24px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 182px;
  height: 32px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 112px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 60px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-15 {
  width: 255px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-16 {
  width: 181px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-17 {
  width: 232px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-18 {
  width: 121px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-19 {
  width: 266px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-20 {
  width: 229px;
  height: 58px;
  color: #4d5315;
  font-size: 48px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}

THANK YOU
HTML
<div class="container--0-">
<div class="text-0-1-1">CONTACT US</div>
  <div class="text-0-1-2">Thank you so much taking the time to attend</div>
<div class="text-0-1-4">THANK YOU!</div>
  <div class="text-0-1-5">our event. Your presence made it even more</div>
  <div class="text-0-1-6">special, and we’re greatful for your support.</div>
  <div class="text-0-1-7">Email</div>
  <div class="text-0-1-8">saveetha@gmail.com</div>
  <div class="text-0-1-9">Phone No:</div>
  <div class="text-0-1-10">6374386670</div>
  <div class="text-0-1-11">9062122984</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 1299px;
  top: -498px;
  width: 454px;
  height: 970px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 233px;
  height: 44px;
  color: #f71dc0;
  font-size: 36px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 339px;
  height: 19px;
  color: #fee821;
  font-size: 16px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 296px;
  height: 58px;
  color: #fff020;
  font-size: 48px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 423px;
  height: 34px;
  color: #f1e21a;
  font-size: 16px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 354px;
  height: 34px;
  color: #fff020;
  font-size: 16px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 81px;
  height: 39px;
  color: #20e4f9;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 322px;
  height: 39px;
  color: #27f4ff;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 157px;
  height: 39px;
  color: #55ff2f;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 196px;
  height: 39px;
  color: #7bd63f;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 194px;
  height: 39px;
  color: #61ce2b;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
```
# OUTPUT:
![alt text](<Screenshot (70)-1.png>)
![alt text](<Screenshot (71).png>)
![alt text](<Screenshot (72).png>)
![alt text](<Screenshot (74).png>)

# RESULT:
The program to design, devlop and deploy a web application for event reistration is completed successfully.