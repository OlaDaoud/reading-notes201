
# Duckett HTML book: Chapter 7 
## Forms 
Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too

TYPES OF INPUTS : 
* text input
* password 
* text area
* radio button (* pick just one of a number of options*)
* checkbox
* drop down list 
* multiple select box 
* file input box
* submit button
* image button 
* button & hidden elemnts 
* date
* url
* email
* search 


### Grouping Form Elements 
you can use <fieldset>
 

# Duckett HTML book: Chapter 7 
## Lists, Tables and Forms

* ### Bullet point styles 
#### list-style-type

- Unordered Lists
For an unordered list you can use the following values:
![](/images/r9-7.png) 

- Ordered Lists
For an ordered (numbered) list you can use the following values:
**decimal**
1 2 3
**decimal-leading-zero**
01 02 03
**lower-alpha**
a b c
**upper-alpha**
A B C
**lower-roman**
i. ii. iii.
**upper-roman**
I II III

* ### Images for bullets 
You can specify an image to act as a bullet point using the  : `list-style-image property`


## tables : 
Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 









**********************************************
# Duckett JS book: Chapter 6 
## EVENTS

**DIFFERENT EVENT TYPES**
![](/images/r9-1.png)

**HOW EVENTS TRIGGER JAVASCRIPT CODE**
1. SELECT ELEMENT 
2. SPECIFY EVENT
3. CALL CODE 

**THREE WAYS TO BIND AN EVENT TO AN ELEMENT**
1. HTML EVENT HANDLERS (*bad practice*)
2. TRADITIONAL DOM EVENT HANDLERS 
![](/images/r9-2.png)
![](/images/r9-3.png)
3. DOM LEVEL 2 EVENT LISTENERS
![](/images/r9-4.png)

**USING PARAMETERS WITH EVENT HANDLERS & LISTENERS**
![](/images/r9-5.png)

### **EVENT FLOW** 
![](/images/r9-6.png)

The flow of events is very important when the event handler is on an element and one of its ancestors or descendant elements.

* Event Object : When an event occurs, the event object tells you information about the event, and the element it happened upon. it is used to : 

• Which element the event happened on If you need to pass arguments
• Which key was pressed for a to a named function, the event keypress event object will first be passed 
• What part of the viewport the anonymous wrapper function user clicked for a c1ick event (this happens automatically); (the viewport is the part of then you must specify it as a the browser window that parameter of the named function shows the web page).


* EVENT DELEGATION : 
- Because events affect containing (or ancestor) elements , you can place event handlers on a containing element and use the event object's target property to find which of its children the event happened on.
- By attaching an event listener to a containing element, you are only responding to one element (rather than having an event handler for each child element).

