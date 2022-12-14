## The Basics of the Swift Programming Language

### Camel Case
A large amount of swift programmers use the "camel case" naming for naming variables

Camel case can be used by making the first letter uncapitalized and then capitalizing the first letter of each following word without using spaces

A couple examples would be ````myVariable, listOfFruits, and namesOfBeaches````

It is not required to use camel case when coding in Swift, but it can help other programmers understand your code better and keep code consistent between programmers

### Variables

A variable is a value that can be altered depending on changes in the program.

In Swift, like every other programming language, variables are essential to making a program that works effectively.

To define a variable in Swift, you will use the ````var```` keyword.

**Project:** Make a variable that contains your favorite website and change the value in the next line.

<img width="1420" alt="Favorite Website" src="https://user-images.githubusercontent.com/101684827/192933428-6880fd8d-f5ff-448c-b058-29beb22be749.png">

### Constants

Unlike a variable, a constant cannot be altered within the program and will throw an error if the program attempts to change its value.

Constants are useful because they allow programmers to have values they know will stay the same throughout the program no matter what happens.

To define a constant in Swift, you will use the ````let```` keyword.

**Project:** Make a constant that contains what your favorite movie is.

<img width="1420" alt="Favorite Movie" src="https://user-images.githubusercontent.com/101684827/192932988-43fe1fe9-d82f-4373-a98c-84f924e3a173.png">

### Arrays

Arrays are used to store multiple items of the same type of data.

Arrays are useful because they can be modified easily and specific items within the array can be chosen very easily.

**Project:** Make an array that contains what your favorite foods are.

<img width="1430" alt="Favorite Foods" src="https://user-images.githubusercontent.com/101684827/192934284-3babfaca-744a-4a90-8cc2-aefc55b6eae0.png">

Arrays can be an easy way to access data.

The index of an array always starts at ````0```` for swift and this will obtain the first value in the array.

The index can be increased or decreased to find other elements in the array.

**Project:** Get the first food from the array data and store it to a variable.

<img width="1386" alt="First Food" src="https://user-images.githubusercontent.com/101684827/192934282-0dab299f-584f-41ed-8d7e-2256b3bbfb15.png">

To add an item to an array, use the name of the array then append with what you want to add in parenthesis ````myArray.append("Something")````

**Project:** Add a fruit to the foods array

<img width="1430" alt="Append to Array Project" src="https://user-images.githubusercontent.com/101684827/193165264-67f5c395-0bec-4bc1-8088-b871b083b9a1.png">

### Dictionaries
Dictionaries are useful because they let you store data in a key value format

Using dictionaries, you can access specific data from its key

For example
````
var someDict:[Int:String] = [1:"One", 2:"Two", 3:"Three"]
````

### Printing
In Swift, printing something to the output is extremely easy

Using the ````print```` keyword, you can print a string and other values that are not strings will be automatically converted to strings

An example of printing a string is:
````
print("Hello world!")
````

**Project:** Define a variable and print it to the output

<img width="1430" alt="Print Project" src="https://user-images.githubusercontent.com/101684827/193165003-a1d49fb9-92cf-46de-964d-544a7a28051d.png">

### Comments
Using ````//```` in front of anything, you can comment it out and it will not impact the rest of the program

Comments can be used for removing code temporarily, explaining what code does, and writing messages within code

An example of commenting something is:
````
//This code prints "Hello world" to the output
print("Hello world!")
````

**Project:** Write a simple comment

<img width="1430" alt="Simple Comment Project" src="https://user-images.githubusercontent.com/101684827/193165705-d72d88d3-5a68-498c-97a2-1ff1076b21a1.png">

You can also comment out much more code at once through using ````/*```` and ````*/```` to make a multi-line comment

An example of a multi-line comment is:
````
/*
This code prints "Hello world" to the output
This code also is very important to the program
*/
print("Hello world!")
````
