---
layout: essay
type: essay
title: "Code has Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-02-06
published: true
labels:
  - Reflection
  - Experience
  - Questions & Answers
  - ESLint
---
<img class="img-fluid" src="../img/ESLint.png">

## Professionalism
Programming, while it does come down to how the computer interacts with the information. It can be just as important for others to be able to read and interpret to understand what your goal is for the project. If someone were to go and reverse engineer, (which of course some may not like) or collaborate with your progress, they would need to see the steps of how you got there or see what is yet to be completed. Especially for the latter, as this would reflect professionalism in one’s work. Luckily, so far in ICS 314, we have been introduced to a program called ESLint! A program that is built to “Find and fix problems in your JavaScript Code”.
## ESLint
After working with ESLint in IntelliJ for about a week, I can say that the program has its ups and downs. Unlike working in JSFiddle though, the program seems to be overall much more stable to be programmed in which is something I am really happy about! As for ESLint itself, it does get pretty tedious as it does point out every little thing. While this is its job since this program statically analyses code, I wish it would give out more suggestions on how to change something in what it could think is correct and save time overall. This is not to say that there is no suggestion box at all as it helped assist in formatting code layouts. There was one time I incorrectly assumed a format when utilizing underscore. It pointed out said error and made sure I looked back at how a function is used before proceeding. One thing I am relieved about about this program though is that it doesn’t get extremely picky over words that would not be found in the English dictionary. While it does point it out, it doesn’t penalize and remove the green checkmark.  
I also usually never write my code for a const in one line but ESLint came through to show me otherwise that there is a a much more compressed and readable layout to read.
```cpp
 const sumTheSimpleWay = (nums) => _.reduce(nums, function (memo, num) { return memo + num; }, 0);
```
## Alongside Other Plugins
Overall ESLint is something I feel that can be applied alongside other programs! It fulfills a niche that other plugins usually don’t cover and is something that can affect the overall efficiency of the program’s internal output! 
