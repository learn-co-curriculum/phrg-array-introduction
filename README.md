# Array Introduction

## Objectives

1. Define arrays in Ruby. 
2. Learn why arrays are useful. 

## What is an Array?

Imagine you are going apple picking. It's a beautiful fall day and you're picking apple after apple. However, you only have two hands. You're holding 2, 3, 4, even 5 apples but you just can't carry any more. Luckily, you've brought along a basket to contain your apples. 

An array is like a basket––it is a container for a collection of data. Let's take a closer look with the help of the following example.

So far, we've used variables to store information. For example, I could create a variable called `my_name` and set it equal to my name: `my_name = "Severus Snape"`. However, variables only allow us to store one piece of information at a time. 

What if my boss, Headmaster Dumbledore, asks me to deliver the names of all of my students? I could create a bunch of variables like this: 

```ruby
student1 = "Harry Potter"
student2 = "Ron Weasley"
student3 = "Hermione Granger"
student4 = "Draco Malfoy"

etc...
```

Then, I could write a program that passes around these variables *one at a time*. This seems messy though. I could easily forget about a student, for example. Or need to create a new student and then have to hunt through my program for every place I ever passed around all of these individual variables. 

If this was real life, Professor Snape would probably just write down all the students in list form and hand that list to Dumbledore. Well, in Ruby, we can do the same thing using an array.

### Array Definition

An array is like a list but in code form. It is a way for your program to store pieces of data as a *collection*. Arrays can contain any data types in any combination––strings, integers, other arrays, hashes, etc. 

Arrays are declared by listing variable names or literals separated by commas (`,`) and wrapped in square brackets `[``]`. To save our four student from above into an array, we write that in our code like this:

```ruby
students = ["Harry Potter", "Ron Weasley", "Hermione Granger", "Draco Malfoy"]
```

## Why Use Arrays

Arrays store information in list form. It's hard to imagine a program you will write in which you *won't* be dealing with collections of data. Whether you're making a command line game or writing a large-scale web application with many users, data is the name of the game. You may need to list the players of your game and their scores, you may need to list the users of your application. You might have an application that connects doctors and their patients and therefore lists the patients of an individual doctor. This list goes on (pun intended). 

Arrays allow us to store a collection of information in one organized place. Arrays can be named, i.e. set equal to a variable, and we can access data from an array, add data to an array or change the data that is already stored in an array. 

