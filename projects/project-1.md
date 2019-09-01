---
layout: project
type: project
image: images/rps.jpg
title: Rock, Paper, Scissors!
permalink: projects/rps
# All dates must be YYYY-MM-DD format!
date: 2019-02-13
labels:
  - C
summary: Simple Rock, Paper, Scissors simulator programmed in C for ICS 212.
---

<img class="ui medium right floated rounded image" src="../images/rps ex.png">

Everyone knows the game rock, paper, scissors. The simple hand game you played with your friends to decide who is paying for dinner or who gets to sit in the front seat of the car ride. Well, what if you didn't have any friends to play with but you ask yourself: should I continue doing my homework or should I play some video games instead? Decide with a game of rock, paper, scissors right on your computer!

This program was one of the many assignments that I programmed for ICS 212. As the project suggests, it was progammed using C langugage. The premise of this program was to keep playing rock, paper, scissors with a computer until the the user decides to quit. If the user decides to quit, the program will display the number of wins, loses, and ties made throughout the entire play through. To combat user input error, the program only recognizes inputs 'r' for rock, 'p' for paper, 's' for scissors, and 'q' for quit. Any other input will display an error message. 

This program includes three methods. The main, compare, and compChoice method. The main method is where the number of wins, loses, and ties are recorded. It also seeds a random integer from 1 to 3 which will represent rock, paper, or scissors. The compChoice method takes in the random integer and convertes it to a char 'r', 'p', or 's' and returns it. The compare method compare computer choice and user choice to see who wins. In conclusion, this project was fun to work on, and although it is simplistic, it can be applied to larger scale applications.

Here is some code that illustrates how I compared the user input to the computer input:

```c
int compare(char comp1, char comp2){
	 
	if (comp1 == 'r' && comp2 == 'r') {
		printf("two rocks, so it's a TIE! \n");
		return 1;
	}
	else if (comp1 == 'p' && comp2 == 'p') {
		printf("two paper, so it's a TIE! \n");
		return 1;
	}
	else if (comp1 == 's' && comp2 == 's') {
		printf("two paper, so it's a TIE! \n");
		return 1;
	}
}
```




