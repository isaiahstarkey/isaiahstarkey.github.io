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

