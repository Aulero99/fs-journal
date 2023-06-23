# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > | The two ways to bind data in .vue files is to use either the ':' on objects for example a :title="" tag enables me to |

2. The `SPA` acronym stands for what?

  > | SPA stands for single page app/application |

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > | The biggest upside of using a single page application is the feeling of responsiveness that comes with having data pre-loaded into the application, while multi-page websites will have an edge in first load time, since they inherently transmit less data per request, but once the app is loaded spa apps will be much more responsive. |

4. What does the `onMounted` method in Vue do?

  > | onMounted is called once the page has finished loading into the browser, basically once all the components have been loaded into memory and resources become available, everything in the onMounted will be called. |

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > | A v-model allows vue to track user inputs and track it either in the appstate or locally in the page-instance. We use these a lot for forms, and I think there may also be uses for them outside of forms, like tracking user interaction with elements. |

6. What is the package.json file used for?

  > | the package.json is used to track other repositories of code across many different repositories and enable their use locally, basically it allows us to use other people's code for our own projects. |

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > | v-if, v-else |

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > | The :key attribute assigns a unique identifier for each component in the v-for so that vue can update single elements instead of drawing entire pages repeatedly. |

9. What is the `<slot>` element and what is it used for?

  > | A slot is used in a .vue file for other elements to be inserted into. In the most recent checkpoint I used a slot to inset my form into another .vue file that had all the info for my offcanvas. |
