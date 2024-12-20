# Ex09 Event Registration Web Application
## Date:20-12-2024

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
Home page
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
     />
  <div class="text-0-1-3">FOOD FEST 2024</div>
  <div class="container-0-1-4"><div class="text-1-2-0">REGISTER</div></div>
  <div class="container-0-1-5"><div class="text-1-2-0">LOGIN</div></div>
</div>
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="135"
    height="28"
    viewBox="0 0 135 28"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="135" height="28" rx="14" fill="#110A0A"></rect></svg
  ><svg
    width="130"
    height="27"
    viewBox="0 0 130 27"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="130" height="27" rx="13.5" fill="#120E0E"></rect></svg
  ><svg
    width="133"
    height="28"
    viewBox="0 0 133 28"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="133" height="28" rx="14" fill="#110A0A"></rect></svg
  ><svg
    width="130"
    height="27"
    viewBox="0 0 130 27"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="130" height="27" rx="13.5" fill="#0F0909"></rect></svg
  ><svg
    width="134"
    height="26"
    viewBox="0 0 134 26"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="134" height="26" rx="13" fill="#0F0909"></rect>
  </svg>
  <div class="text-0-1-8">Full Name-</div>
  <div class="text-0-1-9">Gender-</div>
  <div class="text-0-1-10">Reg no-</div>
  <div class="text-0-1-11">Email id-</div>
  <div class="text-0-1-12">Ph no-</div>
  <svg
    width="190"
    height="39"
    viewBox="0 0 190 39"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="190" height="39" rx="19.5" fill="#120E0E"></rect>
  </svg>
  <div class="text-0-1-14">Event to register</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: -493px;
  top: -373px;
  width: 304px;
  height: 588px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-3 {
  width: 312px;
  height: 93px;
  color: #1f1717;
  backdrop-filter: blur(4px);
  font-size: 32px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.container-0-1-4 {
  position: absolute;
  left: 102px;
  top: 437px;
  width: 133px;
  height: 52px;
  background-color: #1f1717;
  justify-content: start;
  align-items: start;
}
.text-1-2-0 {
  width: 106px;
  height: 24px;
  color: #ffffff;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.container-0-1-5 {
  position: absolute;
  left: 104px;
  top: 362px;
  width: 131px;
  height: 46px;
  background-color: #1f1d1d;
  justify-content: start;
  align-items: start;
}
.text-0-1-8 {
  width: 106px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 83px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 77px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 87px;
  height: 24px;
  color: #ffffff;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 65px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 156px;
  height: 23px;
  color: #ffffff;
  font-size: 19px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
```
event page
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><svg
    width="296"
    height="47"
    viewBox="0 0 296 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
  >
    <path
      d="M0 5C0 2.23858 2.23858 0 5 0H291C293.761 0 296 2.23858 296 5V42C296 44.7614 293.761 47 291 47H5C2.23858 47 0 44.7614 0 42V5Z"
      fill="url(#pattern0_4_13)"
    ></path>
    <defs>
      <pattern
        id="pattern0_4_13"
        patternContentUnits="objectBoundingBox"
        width="1"
        height="1"
      >
        <use
          xlink:href="#image0_4_13"
          transform="matrix(0.000531049 0 0 0.00334448 -0.0278631 0)"
        ></use>
      </pattern>
      <image
        id="image0_4_13"
        width="1988"
        height="299"
        xlink:href="data:image/png;base64"
              ></image>
    </defs></svg
  ><svg
    width="150"
    height="33"
    viewBox="0 0 150 33"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="150" height="33" rx="16.5" fill="#0F0909"></rect></svg
  ><svg
    width="146"
    height="33"
    viewBox="0 0 146 33"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="146" height="33" rx="16.5" fill="#110A0A"></rect></svg
  ><svg
    width="144"
    height="30"
    viewBox="0 0 144 30"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="144" height="30" rx="15" fill="#120E0E"></rect></svg
  ><svg
    width="145"
    height="30"
    viewBox="0 0 145 30"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="145" height="30" rx="15" fill="#0F0909"></rect></svg
  ><svg
    width="146"
    height="33"
    viewBox="0 0 146 33"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="146" height="33" rx="16.5" fill="#120E0E"></rect></svg
  ><svg
    width="146"
    height="34"
    viewBox="0 0 146 34"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="146" height="34" rx="17" fill="#110A0A"></rect>
  </svg>
  <div class="text-0-1-8">*Naan</div>
  <div class="text-0-1-9">*Lemon Chicken</div>
  <div class="text-0-1-10">*Kunafa</div>
  <div class="text-0-1-11">*Mutton Pullao</div>
  <div class="text-0-1-12">*Dragon Chicken</div>
  <div class="text-0-1-13">*Wattermellon Juice</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: -886px;
  top: -373px;
  width: 307px;
  height: 588px;
  background-color: #a08e8e;
  justify-content: start;
  align-items: start;
}
.text-0-1-8 {
  width: 102px;
  height: 44px;
  color: #f908c9;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 160px;
  height: 40px;
  color: #09d944;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 205px;
  height: 37px;
  color: #d91e1e;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 150px;
  height: 29px;
  color: #0da4d2;
  font-size: 17px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 175px;
  height: 40px;
  color: #d9d30b;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 242px;
  height: 65px;
  color: #baabab;
  font-size: 12px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
```
Registration page
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="135"
    height="28"
    viewBox="0 0 135 28"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="135" height="28" rx="14" fill="#110A0A"></rect></svg
  ><svg
    width="130"
    height="27"
    viewBox="0 0 130 27"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="130" height="27" rx="13.5" fill="#120E0E"></rect></svg
  ><svg
    width="133"
    height="28"
    viewBox="0 0 133 28"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="133" height="28" rx="14" fill="#110A0A"></rect></svg
  ><svg
    width="130"
    height="27"
    viewBox="0 0 130 27"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="130" height="27" rx="13.5" fill="#0F0909"></rect></svg
  ><svg
    width="134"
    height="26"
    viewBox="0 0 134 26"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="134" height="26" rx="13" fill="#0F0909"></rect>
  </svg>
  <div class="text-0-1-8">Full Name-</div>
  <div class="text-0-1-9">Gender-</div>
  <div class="text-0-1-10">Reg no-</div>
  <div class="text-0-1-11">Email id-</div>
  <div class="text-0-1-12">Ph no-</div>
  <svg
    width="190"
    height="39"
    viewBox="0 0 190 39"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="190" height="39" rx="19.5" fill="#120E0E"></rect>
  </svg>
  <div class="text-0-1-14">Event to register</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: -493px;
  top: -373px;
  width: 304px;
  height: 588px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-8 {
  width: 106px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 83px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 77px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 87px;
  height: 24px;
  color: #ffffff;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 65px;
  height: 24px;
  color: #f8eded;
  font-size: 20px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 156px;
  height: 23px;
  color: #ffffff;
  font-size: 19px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
```
End page
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="196"
    height="73"
    viewBox="0 0 196 73"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="196" height="73" rx="36.5" fill="#0F0909"></rect>
  </svg>
  <div class="text-0-1-4">Thank you for registration</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: -103px;
  top: -373px;
  width: 317px;
  height: 588px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-4 {
  width: 191px;
  height: 46px;
  color: #f908c9;
  font-size: 19px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
```

## OUTPUT:
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
