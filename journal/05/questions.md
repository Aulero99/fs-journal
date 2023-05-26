# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create Read Update Delete |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | C - Post, R - Get, U - Put, D - Delete |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | ORM stands for Object-Relational Mapping, in MongoDB we dont actually use ORM, but rather ODM because Mongo deals with documents instead of relational data. |

04. Which two `HTTP` request types include a body?

  > | Post and Put, because both deal with making or changing data while get and deletes only deal with the entirety of the data |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | standard, async |

06. What are the three types of data relationships? Provide an example of each.

  > | One to One, or when a single piece of data corresponds to another single piece of data, like ids. One to many, where a single piece of data relates to many other smaller pieces of data like a thread and its comments. Finally the last type of data relationship is many to many, like a server hosting a site with many data relationships, but the server also hosts many unrelated sites. |

07. What is middleware?

  > | Middleware is software thats acts as the middleman between two systems like that of a user and a database. It acts as a middleman to seperate and isolate the computers from one another to ensure data security or ease of use |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | req, res (and next) |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | http://url/api/?tag=winter |

10. What is a ***virtual property***?

  > | Virtuals are additional parameters for a model that reference other files for information |
