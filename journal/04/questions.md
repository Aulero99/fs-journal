# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > | Synchronous code runs 'all at once' from beginning to end, while async code runs in parallel to your code, resolving at different times |

02. What is an event listener?

  > | an event listener is a method used to call functions whenever there is either a change in a variable in the AppState or whenever a function calls an .emit on that variable |

03. What does *REST* stand for, and in simple terms what does it mean??

  > | REST stands for Representational State Transfer Architecture and in laymans' terms these Apis have a uniform interface, meaning they all give back the same response regardless of how a request is made, are independant of the clients applications, are stateless, meaning that hey store no data regarding cliens nor do they require server-side sessions, have a high amount of cachebility, meaning that a response may be cached either on the Api or the client side, have a layered architexture, meaning that requests go through layers making it harder to impossible to tell the identity of either the client or the api, and finally are able to provide either fully static responses, or in special cases provide code that it already formatted and ready to run. |

04. What is a callback / higher order function?

  > | A higher order function is a function that takes in another function as an argument and uses that function as part of its internal logic |

05. What is a `promise`? How do you capture an error from a `promise`?

  > | When using an API, a promise is an object representing the Api's intention in completing the requested task, which allows the code to continue running. In order to capture an error using the promise, a try/catch method must be implemented where the try calls the promise and the catch reports an error if there ever is one. |

06. Name three processes used to make requests over `HTTP`?

  > | Get, Head, Post, Put, Delete, Connect, Options, Trace, Patch |

07. What does the `API` acronym stand for?

  > | Application Programming Interface |

08. What must you do in order to `await` a promise inside of a function?

  > | you have to async the function, and usually you will also use a try/catch controller function to report the error if/when it throws one |

09. What is the purpose of encapsulation in programming?

  > | The purpose for encapsulation in programming is legion, but the biggest reasons I can think of are 1 - Because it keeps your code organized, and therefore makes larger and more complicated projects easier to work in, and 2 - because it isolates errors to their own sections and makes debugging both easier as well as less destructive to the app as a whole if a bug is found |

10. What is `HTTP` response code for a successful request?

  > | 2XX or 200 - 208 and 226 with 200 being the 'all is good' with 201/202 being variations on that|

11. What is a 400 error?

  > | ANSWER HERE |
