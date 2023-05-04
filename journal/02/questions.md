# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | var, let, const |

02. What is the definition of a function?

    > | a function is a set of tasks in javascript bound together in an area that can invoked by 'calling' it at any time |

03. What are the `SOLID` principles?

    > | according to baeldung.com the SOLID stands for 
    Single Responsibility
    Open/Closed
    Liskov Substitution
    Interface Segregation
    Dependency Inversion
    and while I don't really get the gist of the -LID yet, the gist of it is that you want every part of your code to do a single thing and nothing else and not to pigeonhole itself into only working with a narrow dataset. The S states that you want each function to handle a single thing, nothing else. The O means that you want your function to be able to ingest any amount of data but not be edited. The L, well I don't really get the L, but I think it means that any new functions shouldn't break the existing ones. I think the I means that you should avoid grouping tasks together if you can handle them individually. Finally the D means to use locally available variables instead of global variables and use abstraction when possible.
|

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | there are a few ways to remove pineapple. the first would be to replace it with an empty index fruit[2] = ''  which would delete pinapple but leave the index in the array open. The next would be run a function that moves pineapple to the end then pops it ```(fruits[2] = fruits[4] fruits.pop() )``` and this would delete the pineapple from the array, but it would change the location of strawberry to where pinapple was. |

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

    > | function friends(pers,frnd){
        pers.friends.push(frnd)
    } 
    friends(you,them)
    friends(them,you)
    |

06. Give an example of a JavaScript `Conditional`:

    > | According to the MDN Web Docs a conditional is 'condition ? exprIfTrue : exprIfFalse' or just a fancy way to write an if/else statement in shorthand |

07. What is the main difference between `parameters` and `arguments`?

    > | an argument is what is supplied to a function, while a parameter is what the function uses when applying its logic. For example if I have 'function is(thing){}' in my javascript the 'thing' in there is the parameter and anytime I call is() I can supply any argument to it like is('cheezeburger') |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | You can rely on the errors pooped out to the console to locate errors in the code or run a debugger script to stop the code line by line till you find the issue. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | Primative values include numbers, strings, booleans, null, undefined and symbols. These value are stored in the computer memory and have very little logic associated to them. Refence value instead are not stored in memory and reference another location for code instead of being stored in memory and includes things like objects, arrays or functions and often have either a lot more data or more logic associated with them. |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(let i = 99; i > -100 ; i--){
        console.log(i)
    } |
