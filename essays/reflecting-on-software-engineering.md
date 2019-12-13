---
layout: essay
type: essay
title: Reflecting on Software Engineering
# All dates must be YYYY-MM-DD format!
date: 2019-12-10
labels:
  - Software Engineering
---

As my experience with ICS 314 comes to an end, I believe that it is only right to reflect on what I have learned and the knowledge that I have gained along the way. In terms of software engineering, the course gives you a solid foundation to further your software developing career. I feel like the skills and the material that I have learned in this class will still be relevant to me way after I have finished the class, and I cannot say that about many of the other classes that I have taken in the past. There are many fundamental concepts in software engineering that was brought up in this class that go beyond the scope of just web development, and I believe that all software engineers should be familiar with these concepts. 

## The Fun in Functional Programming

One concept of software engineering that we learned about was functional programming. As someone who is still a beginner in programming, I was surprised to see how elegant and easy it is to write functional programs. It makes programming much more efficient by writing less lines of code to do a certain function. In this class we used the underscore library with Javascript to do simple functions, and sometimes not so simple functions, to get the desired results. Why would anyone want to write a for loop like this:

```
for (i = 0; i < array.length; i++) {
	var value = array[i];
	for (j = 0; j < value.stuff.length; j++) {
		doWorkOn(value.suff[j]);
	}
}
```
When you could be using the underscore library to write code like this:

```
_.each(array, doWorkOn);
```
Both pieces of code have the same function, but as you can see, the underscore version is much cleaner, shorter, and simpler to write. 

There is no doubt that functional programming is much more effective than your traditional way of programming, but functional programming is much more than just writing the code. When you code with functional programming it allows you to think of different solutions to problems that you didn’t think was possible. As programming progresses and as different demands arise, functional programming will always be there to add new functions that take on these demands. 

## The Importance of Coding Standards

As I progressed in this class and started to work with others rather than individually, I know much more about how coding standards are important. First of all, what are coding standards? Coding standards are sets of rules and procedures that can be specified on different programming languages or development environments. Now when it comes to coding standards, the question that I have asked myself a handful of times is "are coding standards really necessary?" Of course I want the code that I write to be pretty and uniform as possible, but is it possible for coding standards to have a greater function rather than just making your code look good? I for one think it does.

Coding standards are much more important when working within a group. It helps keep everything and check and code looking uniform. Every programmer has a certain style or way that they like to program, and coding standards allow programmers to know how things should be styled. Without coding standards, I feel like coding in a group would be much more difficult. There may be times where you don’t understand how a certain piece of code was written, but with coding standards you would know exactly how everything should be because you are coding under the same set of coding standards. 

Coding standards aren't designed to stop you from programming a certain way. Coding standards only help you become a better programmer by guiding you through your mistakes. If every programmer used them now, there will be much less headache in the future when you have to go back and update your code.

