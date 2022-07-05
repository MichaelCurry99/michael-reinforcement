Please create an HTML and Javascript file to complete the exercises.
DO NOT write the  exercise solutions in this file. thx! :)


Answer the questions below, then complete the exercises

- Question 1 
    What is a function in JS?
    A function is what holds many types of coding, and usually has paramaters to have it working correctly.
- Question 2
In your own words, why do we use functions in Javascript?
We use them to call different parts of our code.
- Question 3
In your own words, when should we use a function?
     Use a function to hold in specific code to perform specific things.
- Question 4
 What is a higher order function in Javascript? (requires research on your own ;))
     







### Exercise 1

Define a function max() that takes two numbers as arguments and returns the largest of them. Use the if-then-else construct available in Javascript.

function max(6,18){
if(6<18){
alert("6 is less than 18.");
}
else if(18<6){
alert("18 is greater than 6.");
}

return 18;
}
max()

### Exercise 2

Define a function maxOfThree() that takes three numbers as arguments and returns the largest of them.

function maxOfThree(5,8,6){

    if(8<6<5){
        alert("8 is greater than both 5 and 6");
    }
    else if(6<8>5){
       alert("6 is less than 8, while 5 is also less than 8.")
    }
}
maxOfThree()
### Exercise 3

Write a function that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise.

function character(one,two){

let one = ["one"];
let two = ["two"];



}
character()

### Exercise 4 

Define a function sum() and a function multiply() that sums and multiplies (respectively) all the numbers in an array of numbers. For example, sum([1,2,3,4]) should return 10, and multiply([1,2,3,4]) should return 24.

function sum(){


}sum()

function multiply(){


}multiply

### Exercise 5 
Define a function reverse() that computes the reversal of a string. For example, reverse("jag testar") should return the string "ratset gaj".

function reverse(){
let reverse = ["hey","yeh"];

if(reverse[0] === reverse[1]){
    return:true;
}
}
reverse()



### Stretch Goal Exercise 1

Write a function `lengths` that accepts a single parameter as an argument, namely an array of strings. The function should return an array of numbers where each number is the length of the corresponding string.

 ["hello", "what", "is", "up", "dude"]; => [5, 4, 2, 2, 4]



## Stetch Goal Exercise 2
Turn all functions you have written into arrow functions [click here for info](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)