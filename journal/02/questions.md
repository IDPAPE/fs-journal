# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > var, const, let

02. What is the definition of a function?

    > A function is a subprogram that does a specific task and can be called over and over again throughout a program, A function will always return a value, undefined if nothing else.

03. What are the `SOLID` principles?

    > S — Single responsibility principle: Classes should have only one job.
      O — Open closed principle: Objects should be open for extension but closed for modification, This means that you should be able to extend the functionality of a function without modifying the function's code. How I understand this is that rather than rewriting your function to add functionality, your functions should be built in a way that you can create a new function that can be call or be called by your old function to add functionality
      L — Liskov substitution principle: This means that every subclass or derived class should be substitutable for their base or parent class. This one doesn't really mean anything to me yet, I think it is trying to say that if you have functions that are more specific versions of a more broad function, that anywhere you use the specific versions, your more broad version should be able to be slotted in instead without causing errors
      I — Interface segregation principle: A client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use. To us, I think this means that your functions should only take as many parameters as they actually use. Instead of having one massive function that does a bunch of things but doesn't always use every parameter, make more functions
      D — Dependency Inversion principle: your code should be built in a way that when changing some of the more basic items of your code, like constants, data like arrays and objects, and basic functions does not result in errors with your code as a whole

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > delete fruit[2]: does not change array length, fruit[2] will be left undefined
      could also do let removedFruits = fruit.splice(2,2), this would remove pineapple, change the length of fruit[] and store pineapple in removedFruits

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.push[them];
      them.friends.push[you];

06. Give an example of a JavaScript `Conditional`:

    > if (x == y)

07. What is the main difference between `parameters` and `arguments`?

    > parameters are defined in the function definition, used in writing the function. Arguments are the variable that you pass into the function when you call it.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > you could use the built in chrome dev tools debugger. With this you can create breakpoints where your code will pause until you tell it to continue. While your code is paused you can inspect the value of whatever variable you want to ensure is correct.

09. What is the difference between a `primitive` value and a `reference` value?

    >  A primitive value could be a number, string, boolean, null, or undefined; essentially anything that a variable can be set to, and each can only store one at a time.
      a reference value could be an object or array. Objects store a set of values or arrays under a name called key. These objects can be primitives or other objects/arrays: `objectName.value`. An array is an ordered list of variables or objects which can be accessed using the name of the array and a numbered location in the array: `arrayName[position]`. (the 1st position of the array is actually numbered 0, so a 5 long array would have 5 positions, 0-4)
      note- from googling it seems that you can store arrays in arrays and objects in objects but there is almost always a better way to approach whatever problem you are trying to solve.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100; i <= 100; i++)
    {
        console.log(i)
    }
