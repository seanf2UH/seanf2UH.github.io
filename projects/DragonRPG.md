---
layout: project
type: project
image: img/Greenfoot_img.png
title: "Dragon RPG"
date: 207
published: true
labels:
  - Java
  - GreenFoot
summary: "A Javabuilt Object Oriented built Video game built with a partner in AP Computer Science Principles in High School"
---

<img class="img-fluid" src="../img/GreenfootGameplay.png">

Dragon RPG is a lite version of common RPG games that being it has less story focus but more about exploring and killing to survive and win. This was built through a series of functions, classes, variables and more all put together to create several different interactions that connect throughout each level
```cpp
 {
  //Basic if statements that when the dragon object is called in a specific world, how it should behave through sec increments
        if (getWorld().getClass() == BBattleing.class){
            if (pattern > -1){
                pattern = pattern - 1;
            }
            if (pattern < 0) {
                pattern = 150;
            }
            if (pattern == 10) {
                setImage("60328L.png");
            }
            if (pattern == 50) {
                setImage("attackL.png");
                FB.play();
                FB.setVolume(85);
            }
        }
}
```
The starts off with a small introduction and it is up to the user to star exploring and jump straight into the battles! But be careful! :

<hr>

<pre>
You've been informed that dragons have suddenly taken over your hometown! But where are they? Seems the
place has been deserted. I better check inside the buildings and see if there is anyone still around...

</pre>

<hr>

Source: <a href="https://drive.google.com/file/d/1WL6mXVdXN5YMaNpwXntmcV8a4UryVgKn/view?usp=sharing"><i class="large github icon "></i>GreenfootDragonRPGGame</a>
