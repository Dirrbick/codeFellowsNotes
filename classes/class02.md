## What is one benefit of JavaScript not enforcing type?
  * It allows the flexibility to manipulate the different types as the code changes.
## What is one downside of JavaScript not enforcing type?
  * It makes it too squishy and when there is too much flexibility it can end up looking like a jumbled mess
## Should the parameters of a function be changed when the function returns? Why or why not?
  * I think that when the function returns it's value at that point in time changes to whatever got returned. I think it should do that because that way you know exactly what you are looking for.
## Describe a type of data that has rules, aside from the given examples of Number, Integer and Float. What are the rules the data should follow?
  * Functions themselves have rules in a sense that each function should do only one job. The more that you put into a single function the more complicated it can be. Some times you can get lost in your own code. Also a plus to making it so that every function only does one thing, it allows you to be able to call that function all across your app. Any file, so long as you call that file after the one that contains the function... or just export/import the module!!


# Vocabulary
  * functional programming: set of guiding principles for software development, where more thought is given to the input and output of functions
  * pure function: a function where given the same inputs, it always returns the same outputs and has no side effects on the application environment
  * higher-order function: any function which takes another function as an argument and/or returns a function. They are often used to abstract or isolate actions within an overarching action.
  * immutable state: immutable means to not change, and the state of an application usually refers to all of the data an application is maintaing at a certain point in time.
  * object: can be a variable, data structure, function or method. Also called instances, are a piece of data recorded in memory and accessible by an identifier.
  * object-oriented programming (OOP): set of guiding principles where an application is thought of as a collection of objects interacting with one another
  * class: a blueprint for an object, specifying how that object should be created, what initial data values it has, and what actions can be done upon this object through class methods
  * prototype: blueprint of an object. In JS everything is based on a generic "object" class, which is not directly editable by developers. We can change this by accessing the prototype of any instance
  * super: the Keyword refers to the parent class of the current class you're developing
  * inheritance: process of basing an object or class upon an existing "parent" object or class. Allows the "child" to acquire all the variables and methods specified by the "
  * constructor: a function that defines how an object should be created. JS objects innately inherit from a generic "object" class, we usually don't have to define much in a constructor other than the initial values of any custom variables
  * instance:a single object created based on a class or data type's specifications. Only exist while the application is running
  * context: used to represent the current scope or environment you're operating in
  * this: used to refer to the current context; the current object, class or function you are in