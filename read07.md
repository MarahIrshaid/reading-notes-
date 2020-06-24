# Chapter 1: Summary pages 1-24:

Java script can be used either to access content or to modify content
 , RELOAD PART OF PAGE or filtering data


# pages 74-79:

**types of expressions:**

1. Expressions that just assign value to a variable:

var color = 'beige'; 


When you first declare a variable using the var
keyword, it is given a special value of undefined.
This will change when you assign a value to it.
Technically, undefined is a data type like a number,
string, or Boolean.

2. EXPRESSIONS THAT USE TWO OR
MORE VALUES TO RETURN A
SINGLE VALUE 

 var area = 3 * 2;
The value of area is now 6. 


#### Operators:
+ , - , * , / , = , < , > , && , || , !

++ . -- . % 


# pages 88-94 :


EX:
function sayHello() {
    document.write('Hello!)
}

call a function :
sayHello();

when you want the script to perform a task , call the function.

**Declare functions that need information , parameters are information:**

function gerArea(width, height ){
    return width * height ;

}
 width & height are parameters.
then assign values to parameters 
like: 
get area(3,5) or define variables before the function
the va;ues ypu passed to the code are called arguments.

**getting values form a function:**

function myFunction() {
  return Math.PI;
}