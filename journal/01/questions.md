# Foundations of Web Development
01. In your own words, why do we use Git?
    > | Git is a content control system, not to be confused with github, that allows multiple people to work on content at the same time by managing and tracking changes then applying those changes onto a central repository, in addition it also timestamps and allows comments on those changes, which in turn makes it easier to roll back code if needed. |

02. In the terminal, what is the command `mkdir` used for?
    > | It is used to make a directory using a command line |

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > | A Psudo-Class is class derived from another class, usually resulting from the actions of the user. For example :hover applies new rules to the class in question (ie .button:hover) when the user hovers over an that element. I think that :hover is also going to be the most common pseudo-class I use, but I have also used classes like :after, :before, and :last-child in the recent projects  |

04. What is ***specificity*** and how might you use it to your benefit?
    > | Specificity is the order of priority that things are apllies in. For example, class has a lower specificity then ID, therefore anything attempting to change an object using a class will be overridden by something attempting to alter that same thing using an ID |

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > | If I overused the '!important' feature I think I would run into a lot of issues on styling larger projects or in collaborative projects or getting some javascript to work. For example there could be multiple styles/ids trying to set the z-height of an object, and if a snippet of javascript someone else made altered it's z-height to somewhere outside my standard range that I had !important on it could run into issues were that javascript, even if it should have worked, would never work. |

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > | The three components of a CSS rule are the Selector, Property and Value. The selector selects the object in the HTML, the property assigns what we are doing to it (in the exaple above we are changing the text color), and the value is what we are changing the value to. |

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > | Good design incentivizes more interaction with the site and therefore fosters more turnover of sales or services of the website |

08. What is the purpose of ***wireframing***?
    > | The purpose of wireframing is to develop a framwork that works across multiple veiwing sizes and devises without breaking the webpage's content. by making the content in the site dynamic through the use of wireframes the web designers and coders don't have to consider the screen sizes as much and allows fir virtually all size screens veiw the content without much issue. |

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > | While wireframes take some more time to implement into a website, they also make it infinitely easier to adapt the design to differeing screen sizes. Therefore they are not just important, they are arguably the most important aspect of good design practices |

10. Define the display `:flex property:`
    > | Display flex is the evolution of display float, which was the evolution of display block. It is the new standard of wireframes in the current web development world. The flex property allows for you as a coder to dynamically set areas within your code as you see fit, including centering elements vertically which was an actual pain using float. I mean I probably still have a snippet of javascript somewhere to hackily get a float element to center vertically, but again it was a hacky way that involved a lot of math and only sometimes worked and didn't function under no-script machines.  |

11. What `CSS` properties affect the size of a box model?
    > | The bootstrap box model use the col-N style to define the box area for an given section. Beyond that the width: and height: styles affect the corresponding traits of the bod. Inside the box model the padding and margin also determine the space a box takes up alongside the border if there is any.|
