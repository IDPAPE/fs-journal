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

    > | ANSWER HERE |

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

    > | ANSWER HERE |

06. Give an example of a JavaScript `Conditional`:

    > | ANSWER HERE |

07. What is the main difference between `parameters` and `arguments`?

    > | ANSWER HERE |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | ANSWER HERE |

09. What is the difference between a `primitive` value and a `reference` value?

    > | ANSWER HERE |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | ANSWER HERE |
