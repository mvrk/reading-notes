## HTML Chapter 3: list

**Ordered lists** are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.

```javascript
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
		
minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```

**Unordered lists** are lists that begin with a bullet point
(rather than characters that indicate order).

```javascript
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```

**Definition lists** are made up of a set of terms along with the
definitions for each of those terms.

```javascript
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>
```
### Summary
>There are three types of HTML lists: ordered,
unordered, and definition.

>Ordered lists use numbers.

>Unordered lists use bullets.

>Definition lists are used to define terminology.

>Lists can be nested inside one another.



## Chapter 13: HTML Boxes

### Dimensions

### limiting width

### limiting height

### Border, Margin& Padding

### CSS3

```css
<!DOCTYPE html>
<html>
<head>
		 <title>Boxes</title>
		 <style type="text/css">
			 body {
				 font-size: 80%;
				 font-family: "Courier New", Courier, monospace;
				 letter-spacing: 0.15em;
				 background-color: #efefef;}
			 #page {
				 max-width: 940px;
				 min-width: 720px;
				 margin: 10px auto 10px auto;
				 padding: 20px;
				 border: 4px double #000;
				 background-color: #ffffff;}
			 #logo {
				 width: 150px;
				 margin: 10px auto 25px auto;}
			 ul {
				 width: 570px;
				 padding: 15px;
				 margin: 0px auto 0px auto;
				 border-top: 2px solid #000;
				 border-bottom: 1px solid #000;
				 text-align: center;}
			 li {
				 display: inline;
				 margin: 0px 3px;}
			 p {
				 text-align: center;
				 width: 600px;
				 margin: 20px auto 20px auto;
				 font-weight: normal;}
```

## Chapter 2 Basic JS Instructions

### Create an Array

Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).

```javascript
var colors
new Array('white ' ,
'black',
'custom ' );
var el = document.getElementByid( ' co lors ' );
el.innerHTML = colors.item(O);
```

## Chapter 4: “Decisions and Loops” from switch statements

>if...else

>switch case

>truthy falsy

>loops
for, while, do...while

### Summary

Conditional statements allow your code to make
decisions about what to do next.

Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.

Logical operators allow you to combine more than one
set of comparison operators.

if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.

switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).

Data types can be coerced from one type to another.

All values evaluate to either truthy or falsy.

There are three types of loop: for, while, and
do ... while. Each repeats a set of statements.