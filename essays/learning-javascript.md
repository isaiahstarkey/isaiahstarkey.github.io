---
layout: essay
type: essay
title: Learning Javascript
# All dates must be YYYY-MM-DD format!
date: 2019-09-05
labels:
  - Javascript
---

<img class="ui tiny right spaced image" src="../images/degree_difficulty.jpg">*Difficulty: a thing that is hard to accomplish, deal with, or understand.*

What does one think when they hear the word Javascript? When I first heard of it, I thought it would be a language similar to Java. Although there are some similarities regarding both Java and Javascript, one must treat Javascript as an entirely new programming language with its own quirks.

Whether you think Javascript is a good programming language, or whether you think it is a horrible one, you cannot deny that it is used in real life applications and programs. So, if you are on the edge as to whether or not you should learn Javascript, here are some things I’ve come across during my brief time with Javascript. 

## If I can do it, you can too!

As of writing this essay, I may only have around 2 weeks using Javascript, and although I am still familiarizing myself with the language, I must say that it is quite refreshing and easy to digest. I, myself, have experience working with other languages such as Java, C, and C++, and I think Javascript is one of the easier languages to start programming on. Even if you didn’t have any experience with programming, Javascript is a great place to start, and there are websites out there that make it easy to hop right into it, such as freecodecamp.org.

## The powerful tools of Javascript

Speaking of freecodecamp, doing the Javascript exercises on the site was my first introduction to basic Javascript and ES6. While working on the basic Javascript exercises, the main thing I noticed was how lenient it was. Javascript doesn’t use all the different data types that Java or C programming uses. In Javascript, you can use ‘var’ to represent an integer, character, or even a string. This makes this much less confusing, and in my opinion, better than using specific data types.

ES6 is where things start to get interesting. ES6 introduces some powerful features that can make your programming life much easier. For example, I was able to use the spread operator, which allowed me to expand an array and copy values to another array.

```javascript

const arr1 = ['JAN', 'FEB', 'MAR', 'APR', 'MAY'];
let arr2;
(function() {
 "use strict";
 arr2 = [...arr1]; // spread operator used to copy contents into arr2
})();
console.log(arr2);

```
Another function that I think is very useful in ES6 are arrow functions as it  allows the user to write concise functions. Concatenating two arrays or writing anonymous functions takes less lines of code to write with arrow functions and they simply look better as well.

```javascript

const concat = (arr1, arr2) => arr1.concat(arr2);

console.log(concat([1, 2], [3, 4, 5])); //returns 1,2,3,4,5

```

## In the context of relationships

So in the end, we realize that all engineering and programming is there for a reason - to serve human needs. Maybe that's why those things are difficult, because they both involve humans and are for humans.

Relationships, regardless if they're romantic or not take work. Humans are fickle creatures and relationships can come and go with the wind. To properly maintain something over time requires work. Family takes work. Marriage takes work. We live to figure out what works and what doesn't and hope that as we move forward we're improving.

Relationships have always been difficult, and by nature will continue to be so.
