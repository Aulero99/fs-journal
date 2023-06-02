# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | The entrypoint of an application is where the application starts, basically the first domino that needs to fall for all further dominos (files) to be run. In .vue, that file happens to be main.js, while in html and css that file is index.html etc. |

02. What is the difference between a vue `component` and `page`?

  > | A component is an asset you can reuse on multiple pages, like a lego piece, while a page is something the user can veiw and interact with that is a combination of tis own singular logic and multiple components, kinda like the finished lego set, or the instruction manual depending on how you think of it |

03. What is ***Component-Based Architecture***?

  > | A Component-Based Architxture in the realm of coding is a framework that focuses on re-usable objects that can be repeatedly used all throughout a project. Basically it is an architexture that tries to build self contained lego pieces of code that can be dragged and dropped into more complicated systems without the need of remaking the system |

04. What are the three tags that make up a Vue component?

  > | All .vue files have at least a template and a script tag, with some having a style tag for scss styling if needed. |

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | Lifecycle hooks are pre-defined methods that are executed in a specific order, from the start of a vue launch to its end. For example, a beforeCreate will launch before basically anything else, while an onMount will launch once a specific item has been loaded into memory. |

06. Which component in Vue does the vue-router use to mount pages onto?

  > | The router mounts pages onto the App.vue file, which is read by the browser through the main.js file through the index.html file.  |

07. What is the difference between the `AppState` and the state object within a component?

  > | The AppState.js is the home of all data within the application, while the state is a hot refreshed, or proxied instance of that file, basically it is kinda like the ram or cache on a drive, while the Appstate is more like the solid or non-cached data, slower to refresh and not as responsive, but more permanent in comparison. |

08. What is the responsibility of `Services` in our Vue projects?

  > | In the .vue projects we have done so far, the Service.js files have mostly been responsible with communicating with outside computing elements like api's and appending data to our AppState. Further down the line it will likely also be responsible for manipulating the data even further than that, like how we did in the vanilla MVC applications. |

09. What are ***props*** and how are they used? Provide an example

  > | Props are the hook for the model to relate to a set of data to a specific .vue component. for example, in gregslist we had a car model that we hooked into our CarCard.vue file as a carProp so would could pull data out of the Car.js model as a Car, which meant that the data we got from the api as a pojo got modeled in our appstate then rendered to the component through the prop. |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > | computed(()=> AppState.thing) |
