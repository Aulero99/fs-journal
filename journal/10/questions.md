# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | The purpose of a namespace is to limit the ability of c# files to talk to one another. Basically, if I have a set of files with namespace 'cool' and another with namespace 'story' they could both have identical class name of 'bro' but still not interfere with each other since they exist in different namespaces.  |

02. What is the difference between a `class` and an `interface`?

  > | A class in c# an interface is used to enforce rules in your program, while a class is used as something you can enforce rules on. If I undrstand this correctly, if I were to compare this to, say, a game of baseball, the intereface would be the literal rules or the umpire, while the classes would each be the player or the field, the things the rules act upon. |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | If I remember correctly, the only method we were taught that doesn't return a type is void. |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | The access modifier is the 'public' declaration, which allows global access to the function |

06. In the Car example what is `string` an indication of?

  > | C# is a language that requires you to declare the data type of all variables and return types, unlike javascript which is a much more loose programming language. In this example, the string is declaring the expected return type of the function Start() |

07. In the Car example what is `abstract` preventing?

  > | The abstract, to paraphrase my understanding according to the microsoft  docs, is a modifier that indicates that something is a set of incomplete data. From what I can tell it enables you to run functions - like the start function - to gather more data within it. |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | In an sql table, like in an excel spreadsheet, the data of the table is stored in the rows, while the labels are held in the columns. Basically, each of the columns wil hold a single data type - ie the id column will hold ids while the name column will hold names - while each of the rows will hold a single instance of related data - ie user 23 has name bob etc.|

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > |
  In order to create a table with those particular columns ou would run the following command in your dbsetup file: 
  CREATE TABLE
    characters(
        id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
        name VARCHAR(255) NOT NULL,
        age VARCHAR(255) NOT NULL DEFAULT "misc",
        description VARCHAR(3000) NOT NULL
    ) default charset utf8 COMMENT ''; 
    |

10. In SQL how can you query more than a single table? Provide an example.

  > | There are many ways to get that kind of data back, however the method we have been using is the JOIN method. From Sharplist, one such command was: SELECT alb.*, creator.* FROM albums alb JOIN accounts creator ON alb.creatorId = creator.id WHERE alb.id = 22; this returns a table with data from the albums table and the accounts table joined where the album id is 22.   |
