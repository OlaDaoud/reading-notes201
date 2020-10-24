# Understanding The Problem Domain Is The Hardest Part Of Programming

### Understanding The Problem Domain Is like solving a jigsaw puzzle .

* If you want to make programming easier, you can do one of two things:

1. Make the problem domain easier: by cutting out cases and narrowing your focus to a particular part of the problem.
2. Get better at understanding the problem domain: It is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

* Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.

## From the Duckett JS book

### Chapter 3: “Object Literals” (pp.100-105): 

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,variables and functions take on new names.

#### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES 
#### IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS 

* properties and methods have a name and a value. In an object,that name is called a key. An object cannot have two keys with the same name. This is because keys are used to access their corresponding values. 
* The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function. 

![](images/r6-1.png) 

#### Literal Notation

* To access a property of this object, the object name is followed by a  **dot** (the periodsymbol) and the name of the property that you want.

* Similarly, to use the method,you can use the object name followed by the method name.
hotel . checkAvailability()

* If the method needs parameters, you can supply them in the **parentheses** (just like you can pass arguments to a function).

* If you had two objects on the same page, you would create each one using the same notation but store them in
variables with different names. 

![](images/r6-2.png)

## Chapter 5: “Document Object Model” (pp.183-242)

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

![](images/r6-3.png)

* The browser represents the page using a DOM tree.It have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.

* You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.

* Whenever a DOM query can return more than one node, it will always return a Node list.From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.

* An element node can contain multiple text nodes and child elements that are siblings of each other.

* In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).Browsers offer tools for viewing the DOM tree . 


