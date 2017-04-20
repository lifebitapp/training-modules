# Module 3: Programming Basics with Java

***

## Getting Started

Prior to completing the module below it is highly recommended that you look at the following learning material:

- [Codecademy Java Course](https://www.codecademy.com/learn/learn-java#)

***

## The Test

**Note:** You will stage, commit (with valid message) and push your changes **after each update**.

### Variables, Constants and Strings

1. Create a new Git repo in your GitHub account under your namespace called `Java`. All the code for this module should be committed there.
2. Create a file and define 5 Java constants there via the `define()` method. Assign some constants string values and some integer values. The integer values should be between one (1) and five (5).
3. Stage, commit and push your changes.
4. Create a new file. In the file bring in the file in a way that will make it required and that it will be brought in only one time.
5. Now create an array variable called `array` and assign it an associative array, using key names that are string constants from your file and at least one (1) value that is an integer constant.
6. Now create an integer variable called `result` and assign it the output of the multiplication of two (2) or more array values. In this equation you should use array keys that are constants.
7. Now print out the result as a string in the format of: `"The result of X * Y is: Z"`. Create this message WITHOUT string concatenation and without reassigning any new variables.
8. Now refactor the printed string to use string concatenation.
9. Create a new string variable that holds three (3) multi-line paragraphs of text, this text can be anything you want and should have at least five (5) variable substitutions within the string. You can create the variables to put into this string if necessary. Do not use string concatenation or a multi-line string inside double quotes to create the string's value. Print the string's value.

### Loops & Control Structures

1. Create a new file called `loop-control` and inside create an array called `numbers` which contains integer values between `0` and `100`, with a step of `3` between each number (eg. `0, 3, 6, 9, 12`). Do this with the least amount of code you can.
2. Now create a `foreach` loop to iterate over the array, inside the `foreach` loop add logic to do the following *without* using an `if-else` statement:
    - If the number is 3, print `"Three"` one (1) time  
    - If the number is 9, print `"Nine"` three (3) times  
    - If the number is 15, print `"Fifteen"` five (5) times  
3. Now refactor the logic inside the `foreach` loop to do the following (`if` and `else` can be used now):  
    - If the number is a multiple of `7` print out "Sevens are lucky, this number has X", where `X` is the number multiples of `7` represented by the number  
    - Otherwise, if the number is a multiple of `10`, print out `"X is a round number"`, where `X` is the number  
    - If the number is the first in the group, print out `"First number"`  
    - If the number is the last in the group, print out `"Last number"`  
4. Refactor the code to be a for loop.
5. Refactor the code to be a while loop.
6. Refactor the code to be a do-while loop.

### Functions

1. Create a new file called `functions`.
2. Create four (4) math functions: `add`, `subtract`, `multiply` and `divide` two (2) given parameters.
3. Use all of the functions and print out the result, showing how you would pass arguments to the functions by value and by reference.
4. Create a function which takes two (2) comparison parameters and a third boolean parameter defaulting to false, which tells the function whether or not to compare the data type as well. Have the function print out a string that tells if the parameters are equal or not, and if they are equal in datatype if the third parameter was true.
5. Use the `comparison` function and pass in the following parameters:
    - `4, "4"`  
    - `5, "5", true`  
    - `4, 4.0`  
    - `5. 5.0, true`  

### Classes

1. Create a new class called Math in a file, and copy your previous four (4) math functions into the class as public functions.
2. Refactor each function so it will be able to take a minimum of `2` integer parameters with no maximum number of parameters. (eg. You could pass in `2` arguments or `n`.) The functions should return the relevant operation applied to all the function arguments, in the order they were given.
3. Create a new file called `do_math`, which uses each function in the Math class 3 times and prints out the output.
4. Now refactor your `Math` class to have 4 constants that represent each math operation and a private method called `doOperation` whose first parameter is the type of operation to do, and subsequent parameters are the values to do that operation on. Then, refactor the previous functions to all use the new `doOperation` function.

### Inheritance, Interfaces, Namespaces and Traits

Create a new branch in your Java Git repository called `advanced` and push your code for the following exercises there. Place all the following code in a folder called `advanced`.

1. Create an inheritance hierarchy composed of six (6) classes:
    - Computer > Workstation
    - Workstation > Mac
    - Workstation > PC
    - Computer > Server
    - Server > WebServer
    -	Server > DatabaseServer
2. Create a new Java file called `main.php` which uses these classes. Be creative and show the following concepts (you can simply echo strings for the function logic):
    - Public, Protected and Private functions
    - Public, Protected and Private properties
    - Overwriting inherited functions
    - Overwriting inherited functions but still executing the parent's functionality for that function before implementing the child's logic
    - Refactor your code to show the use of namespaces using the keywords `use` and `as`
    - Now refactor your code to use at least one (1) `interface`
    - Now refactor your code to include at least one (1) `trait` which should contain a function that executes then extends a super class' functionality
    - Now refactor your code to include at least three (3) `closures`. If your code already has this, add three (3) more
    - Stage, commit and push your changes **with a commit message of `closures`**



***

## Wrapping Up

When you are finished, push your code to GitHub. You should have two (2) repos, `java` and `java-final` in your personal GitHub namespace. Create a tag called `v1.2` with a message of `"ready for review"`. Be sure your tags are pushed to the remote repository and are visible in GitHub.

