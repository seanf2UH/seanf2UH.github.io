---
layout: essay
type: essay
title: "Dedicated UI Framework Vs. CSS & HTML"
# All dates must be YYYY-MM-DD format!
date: 2024-02-22
published: false
labels:
  - Reflection
  - Experience
  - HTML & CSS
  - Bootstrap
---
<img class="img-fluid" src="../img/ImgCSS_Vs_BootStrap.png">

# Starting Place
HTML & CSS Hypertext and StyleSheet, respectively, have been a handy tool in creating various websites. Some of these websites can look complicated with various buttons, positioning, headers, navigation bars, etc. Learning how to implement them can turn out to be fairly straightforward with proper utilities by adding their respective width, and dimensions, to their tags such as the ones below. 
## Navigation Bar:
HTML: Uses List
```cpp
<body>

<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

</body>
```
CSS: Reacts to hover selection
```cpp
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 200px;
  background-color: #f1f1f1;
}

li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}

li a.active {
  background-color: #04AA6D;
  color: white;
}

li a:hover:not(.active) {
  background-color: #555;
  color: white;
}
```
Anything was possible at your fingertips with the introduction and continued development of these types of software, but as time continued, there eventually came the rise of several introduced frameworks that allowed what HTML could already do better.

# Bootstrap 
Bootstrap is a UI Framework that we’ve been introduced to in the ICS 314 course. So for now, I’ll be using this as a reference comparison between UI Frameworks and HTML/CSS. But unlike CSS, there is a lot more to learn here as Bootstrap uses completely different components to set up its webpage. Many similar components are present except it is built to be a lot more responsive on the developer side and user-friendly on a variety of devices. Unlike using solely HTML, things such as images, text, and buttons, are affected to match according to the display, and browser and are a lot more consistent to control all around without the need to make adjustments for each webpage. 
A Container Class is a good example of this as this reacts accordingly to the size of the browser.
```cpp
<div class="container">
  <h1>Bootstrap Container</h1>
</div>
```
## Downside:
Of course, however, these are not without their respective downsides. These kinds of frameworks usually have predetermined components and libraries built into them which means there is a good chance that it may not be compatible with certain utilities you may need for your website. Thus it is important to check what this UI Framework is offering and make sure that it lines up with your goals. Otherwise, much more trouble will arise in situations where it could have been avoided. Imagine learning a framework only for a good chunk of it to be wasted because it isn’t compatible with what you wanted it to do.
