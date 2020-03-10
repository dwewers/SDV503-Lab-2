# SDV503-Lab-2


In this lesson we learned about javascript operators.

There wasnt really anything I had trouble with in this lesson since it was all pretty straight forward. It was more about practising over and over until it was stuck in my head.

Operators are symbols that we use in our code when we want to perform a specific action. These include the likes of, add (+), subtract (-), multiply (*), equal (=), devided by (/), less than (<), greater that (>), not (!), and (&&) or (||), and so on. These we very useful as we were able to perform a variety of tasks using them, and will be able to use them for many other tasks in the future. I believe it was important that we learned these as it is quite common to come across these sympols when writing our code.
We started off with Arithmetic operators. These are the basics ones such as addition and subtraction.
An example of code that we wrote was:
let x = 20;
let y = 10;

console.log(x + y)
//since we use the '+' symbol, this equation outputs a value of 30
console.log(x * y)
//since we use the '*' symbol, this equation outputs a value of 200
console.log(x - y)
//since we use the '-' symbol, this equation outputs a value of 10
console.log(x / y)
//since we use the '/' symbol, this equation outputs a value of 2

We then learned about Increment Operators. This increment the value of the variable by one. We identify and increment operator as a '++'

There are two types that we learned, Pre (++x) increment and post (x++) increment. A pre increment, increments the variable by one and then returns the variable. Whereas, a post increment, returns the variable, then increments the value by one.

here are a couple of examples that we learned:

Pre increment:

let x = 10

console.log(x); //logs 10
console.log(++x); //logs 11
console.log(x); //logs 11
console.log(++x); //logs 12

As we can see from this, when we log(x) initially, we get the value of 10. When we then increment it, it adds the value of x as + 1. When we log it again, we then get the new value of x as 11, and so on.

Post increment:

let x = 10

console.log(x); //logs 10
console.log(x++); //logs 10
console.log(x); //logs 11
console.log(x++); //logs 11

As we can see from this, when we log(x) initially, we get the value of 10. When we then increment it, it doesnt post it as +1 yet. When we log it again, we then get the new value of x as 11, and so on. 

What we learn from this is that the difference between the two is that when we pre-increment, it increments the value of x and then executes the expression, whereas a post-increment does the opposite. It evaluates the statement and then increments the value of x.
I think it is important that we learned this as it could mess up our code if we were to get them muddled up.

Next we learned about decrements. These decrease the value of the variable by one each time. unlike increments, we use the symbol '--'
We learned about two different types. These share a similarity to the increments and we have pre (--x) decrement and post (x--) decrement.

here are a couple of examples that we learned:

Pre decrement:

let x = 10

console.log(x); //logs 10
console.log(--x); //logs 9
console.log(x); //logs 9
console.log(--x); //logs 8

As we can see from this, when we log(x) initially, we get the value of 10. When we then decrement it, it subtracts the value of x by - 1. When we log it again, we then get the new value of x as 9, and so on.

Post decrement:

let x = 10

console.log(x); //logs 10
console.log(x--); //logs 10
console.log(x); //logs 9
console.log(x--); //logs 9

As we can see from this, when we log(x) initially, we get the value of 10. When we then decrement it, it doesnt post it as -1 yet. When we log it again, we then get the new value of x as 9, and so on. 

What we learn from this is that the difference between the two is that when we post-decrement, it decreases the value of x and then executes the expression, whereas a post-decrement does the opposite. It evaluates the statement and then decreases the value of x.
I think it is important that we learned this as it could mess up our code if we were to get them muddled up.

Next we learned about String Concatenation. When doing this, we used the '+' to link two or more strings together.
An example of this is:

let a = "hello, ";
let b = "world";

console.log(a + b); // outputs hello world

We learned a better way of doing this which looked like this:

const firstWord = "hello";
const secondWord = " world";

console.log(firstWord + secondWord); //The original way we were taught to print to console using "+"
console.log( `${firstWord} ${secondWord}` ); //This is a different way of printing words to the console without using "+"

Next we learned about strings using numbers.
this looks like this:

console.log(10 + 5);//This prints the value of 15 since both operands are numbers
console.log(10 + "5");//This prints the value of 105 since 10 is a number and 5 is a string. They cant be added like usual, so they are both concatenated
console.log("10" + 5 );//This also gives the value of 105 for the same reason as prior, with the exception of 5 being the number and 10 being the string.
console.log(10 + 10 + "5");// This equation outputs the value of 205. Since both the 10s are numbers, we add those together. But because 5 is a string, we link it to the end.
console.log("10" + "10");//Since both the 10s are strings in this equation, we concatenate them together.

Next was comparison operators. These are used when we want to compare two valuables in a Boolean pattern. 
They look like this :
       
  ==           Equal
  ===          Identical    // check equality of data type
  We dont want to mix the two of these up, since the triple = requires both types to be the same to get a true reading. Whereas the double equal can have two different types.
  
  !=           Not equal
  !==          Not identical //check inequality of data type
  <           Less than
  >           Greater than
  >=          Greater than or equal to
  <=          Less than or equal to
  
  Here are some comparison example that we learned:
  
  console.log(10 == 5); False //False since 10 is not equal to 5  
  console.log(10!= 5); True //True since 10 is not equal to
  console.log(10 < 5); False //False since 10 is not less than 5
  console.log(10>5); True // True since 10 is greater than 5
  console.log(10 <= 5) False //Since 10 is not less than or equal to 5
  console.log(10 >= 5) True //Since 10 is greater than or equal too 5, which in this case, 10 is greater than 5
  
  Here are some examples of comparing a number with a string data type:
  
  When we are comparing a number type and a string type, the string types are converted into number types for the comparisson.
  
  console.log(10 == "5"); False 
  console.log(10 == "10"); True
  console.log(10 != "5"); True 
  console.log(10 != "10"); False
  console.log(10 < "5"); False 
  console.log(10 < "10"); False 
  console.log(10 > "5"); True
  console.log(10 > "10"); False 
  console.log(10 <= "5");False 
  console.log(10 <= "10");True 
  console.log(10 >= "5"); True 
  console.log(10 >= "10"); True
  
  Next was Boolean and Number comparisons. This is where we compare numbers/strings to true/false.
  Like the previous thing we learned, strings are converted into numbers for the comparison.
  
  console.log(true == 1); True // Since we know that true is 1
  console.log(true == "1"); True // Since we know that true is 1, and the string is converted to a number
  console.log(true == 0); False //since we know that false is actually equal to 0
  console.log(false == 1); False // since we know that true is actually equal to 1
  console.log(false == 0); True //since we know false is equal to 0
  console.log(false == "0"); True //since we know false is equal to 0, and the string is converted to a number
  
  console.log(true != 1); False 
  console.log(true != "1"); False 
  console.log(true != 0); True 
  console.log(false != 1); True
  console.log(false != 0); False 
  console.log(false != "0"); False 
  




