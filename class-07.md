## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

- the constructor function is defined using a function expression. 
- The new keyword instantiates (i.e. creates) an object.
- The constructor function initializes properties inside that object using the this variable.
- The object is stored in a variable for later use.
- methods can be added to a constructor function's prototype. 


```html
Summary

Domain modeling is the process of creating a conceptual model for a specific problem. 
And a domain model that's articulated well can verify and validate your understanding of that problem.
Here's some tips to follow when building your own domain models.
When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.
```

## Tables

- Basic table structure
  
```html
<table> 
<tr>
<td>
```
- Table headings
   
```html
<th> 
```
- Spanning rows

- Long tables
  
- Width and Spacing

- Border and background

### Summary

- The <table> element is used to add tables to a webpage.
- A table is drawn out row by row. Each row is createdwith the ```<tr>``` element.
- Inside each row there are a number of cellsrepresented by the ```<td> ```element (or ```<th>``` if it is aheader).
- You can make cells of a table span more than one rowor column using the rowspan and colspan attributes.
- For long tables you can split the table into a ```<thead>```,```<tbody>```, and ```<tfoot>```.


## Functions, Methods, and Objects

- CREATING OBJECTS USING CONSTRUCTOR SYNTAX
  
- CREATE & ACCESS OBJECTS CONSTRUCTOR NOTATION
- Ways to create objects: literal notation and object constructor notation
- This is commonly used inside functions and objects where the function is declared alters what this means
- Key:Value
  <br>
- build in objects: 

>browser object model
>document object model
>global javascript objects

- JavaScript six data types
  >String
  >Number
  >Boolean
  >Undefined
  >Null
  >Object

- Creating an instance of the date object
``` var today = new Date();```

### Summary

>Functions allow you to group a set of relatedstatements together that represent a single task.
<br>
>Functions can take parameters (informatiorJ required to do their job) and may return a value.
<br>
>An object is a series of variables and functions that represent something from the world around you.
<br>
>In an object, variables are known as properties of the object; functions are known as methods of the object.
<br>
>Web browsers implement objects that represent both the browser window and the document loaded into thebrowser window.
<br>
>JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
<br>
>Arrays and objects can be used to create complex data sets (and both can contain the other).