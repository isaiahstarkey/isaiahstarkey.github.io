---
layout: project
type: project
image: images/morse.png
title: Morse Code Translator
permalink: projects/morse
# All dates must be YYYY-MM-DD format!
date: 2019-03-08
labels:
  - C
summary: A C program that translates command line agruments in morse code and translates it into English.
---

<img class="ui image" src="../images/morse ex.PNG">

Morse code is inputted via command line when the program is ran. If the morse code is correct, it will output the the English translation. This program not only translates the English alphabet, but it also translates numbers as well. 

In this project I gained more experience working with C programming and interpreting command line agruments to be used with the code. In order to translate the morse code, I defined an arrary of character for each letter of the alphabet and number 0 through 9. I then did error checking to see if there is more than two command line agruments used to translate. Finally, I looped through the agruments, looped through the morse code arrary, compared arguemnts to morse code, then printed translation.

