# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | The pillars of OOP are 1. Abstraction, moving segments of the code to other areas so users and implementers don't need to understand all the logic behind the code to work with the code 2. Encapsulation, the bundling of code into smaller sections with limited access to some parts, 3. Inheritance, letting one object gain the values and properties o another object  & 4. Polymorphism or having your code applicable in several different ways  |

02. How does `export` differ from `export default`?
  
  > | Export is good when importing multiple values, while export default is good when importing a single value, the only real difference I could find is that the export default gives a fallback to your export of 'default' which could be important to dependencies |

03. What is Encapsulation?
  
  > | Encapsulation is isolating your code into segments that deal with smaller amounts of data and have varied levels of access, this isolated the number of ways a user can interact with the data, and therefore limited the number of circumstances a programmer would need to account for |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | Proxy objects allow for several things such as making aspects of an object (like an ID) into private aspects that the user has little to no access to. |

05. What the difference between a `class` and an instance of a `class`?
  
  > | The difference between a class and an instance of a class, as far as I can tell, boils down to whether or not you are the exporter or the importer of that class. For example, on the model of a Player, the class Player is everything in that file, but to the rest of the files the instance of 
  Player is just that, an instance because they don't see the underlying logic behind that player class, only the import of the instance of Player therefore the difference is between a class and an instnace of that class is whether or not you have access to the logic behind the curtains or not|

06. What is a computed Property?
  
  > | A computed property is a property of an object that has been fed into another function then had some logic applied to it. The main example I could find from the readings was the proxy method of providing a handler for an object then returning computed properties of the object through the handler, in the example the computed property of id would throw an error if the user attempted to access it because it was computed to do that  |

07. What is the purpose of the `MVC` pattern?
  
  > | The purpose of the MVC pattern is to control the flow of data and organize our code into predictable and repeatable patterns that cn be followed by other programmers after we have finished our own job of making the app in question. |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | The job of the controller in the MVC is to pass along inputs from the user and draw the results of those inputs to the page |

09. What is the job of the `Service` in `MVC`?
  
  > | The job of the service in the MVC is to preform 'business logic' or in laymens terms to manipulate the data |

10. What is the job of the `Model` in `MVC`?
  
  > | The job of the model in the MVC dsign pattern is to hold the blueprint of items by passing data through them |
