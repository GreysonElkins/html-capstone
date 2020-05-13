##  How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?

##  There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.

*Numbers* are numeric values. They aren't expressed in quotation marks,

*Strings* are text, letters, and other characters. They are enclosed in quotes.

*Booleans* are true or false items. It is used like a switch, and are helpful in decision making

##  What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?

1. The name must begin with a letter, dollar sign, or underscore. NO numbers.
2. Can contain letters, underscores or dollar signs. Never a dash or a period.
3. You can not use keywords or reserved words.
4. variables are case sensitive, so score and Score are different, but using both is bad practice.
5. Variable names should describe the kind of info the variable stores.
6. Use camel case, i.e. firstName not firstname.

Avoid using default, delete, do, final, int, native, switch, var, with. There are many more.


##  How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?

They are helpful when you don't know how many items are to be included. Arrays are accessed as a numbered list starting at 0. You can declare variables which access the array with a specific index number. To change an item, you call the array with it's index number and declare a new value for it.

##  What is the difference between an expression and a statement?

Statements are instructions for the reader, while expressions result in single data values. Statements : expressions :: sentences : math problems.

##  What are three types of operators and how are they used?

1. Assignment operators assign values to variables.
1. Arithmetic operators perform math.
1. String operators combine strings.

Open up the Chrome Developer Tools, and open the Console tab. This is where we can write some JavaScript! If you don't remember how to get to the console, watch [this video](https://www.youtube.com/watch?v=JzZFccCEgGA) to review.

Pro tip: If you want to write more than one line of code in the console before running the code, then use `shift + enter`.

For each task listed below, enter it in the console:

##   `25`

##  `"this is my string"` (notice the output's color difference between a number and a string)

##   `var myNewString = "Hello Turing!";`

##  `myNewString` Before you hit Enter, what do you expect to see in the console?

"Hello Turing!"

##   `var myNum = 9;`

##   `myNum` Before you hit Enter, what do you expect to see in the console?

##   `var anotherString = "How are You?"`

##   `"Connect" + " " + "these" + " " + "strings."` What happened? This is called string concatenation. Notice the strings with spaces.

the console returns a string "Connect these strings"

##   `myNewString + anotherString` This is also string concatenation using variables.

##   `5 > 3` returns a boolean value of true. How could you change this expression to return false?

I could enter 3 < 5

##   `"2" === 2` and `"2" == 2` Why does one of those expressions return true and one return false?

`==` comparisons convert values into the same data type, `===` does not.

##   `if (8 < 9) {console.log("Hey!")}` Before you enter this code in the console, what do you think will happen? Will it log Hey to the console?

I think it will say "Hey!" and log it to the console.

##   Write an if/else statement where the code in the `else` block is executed. For example: `if (3 < 1){console.log("if block")} else {console.log("else block")}`

![alt text](https://user-images.githubusercontent.com/62047446/77360073-9c8e5a00-6d44-11ea-953e-b3fb6992b6b0.png)

##   Use the console to solve
[these problems](https://s3.amazonaws.com/TrainingNerd/JavaScriptForBeginners/exercises/variables.html).

![alt text](https://user-images.githubusercontent.com/62047446/77360956-3e627680-6d46-11ea-9729-b4f80d9126a3.png)

![alt text](https://user-images.githubusercontent.com/62047446/77361446-31925280-6d47-11ea-8227-15c33acddfb5.png)

![alt text](https://user-images.githubusercontent.com/62047446/77362435-cf3a5180-6d48-11ea-9386-a3243a1f38f3.png)
