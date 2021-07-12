# read07
# Tables :
##  How to create tables ?
## What's a Table? 
## Define an HTML Table
## The <table> tag defines an HTML table.

## Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

## By default, the text in <th> elements are bold and centered.

## By default, the text in <td> elements are regular and left-aligned.
## Example
# ![](https://i.ytimg.com/vi/cZSTrSBTnL8/maxresdefault.jpg)
## HTML table allows you to arrange data into rows and columns. They are commonly used to display tabular data like product listings, customer's details, financial reports, and so on.

## You can create a table using the <table> element. Inside the <table> element, you can use the <tr> elements to create rows, and to create columns inside a row you can use the <td> elements. You can also define a cell as a header for a group of table cells using the <th> element.

## The following example demonstrates the most basic structure of a table.
## Tables do not have any borders by default. You can use the CSS border property to add borders to the tables. Also, table cells are sized just large enough to fit the contents by default. To add more space around the content in the table cells you can use the CSS padding property.
## By default, borders around the table and their cells are separated from each other. But you can collapse them into one by using the border-collapse property on the <table> element.

## Also, text inside the <th> elements are displayed in bold font, aligned horizontally center in the cell by default. To change the default alignment you can use the CSS text-align property.
# Table Header
## An HTML table contains a set of columns and actual data rows and each row consists of one or more cells, which can be either header or data cells. Header information in a table is defined with the < th > tag.
## The < th > element defines a header cell in a table. The < th > elements are contained within a < tr > element , which may also contain < td > elements for data cells.
## HTML Table Caption
## A < caption > .. < caption > tag of a Table represents the title of the table, it should tell what the table is about. The caption text should be relatively short, but informative.
##  ![](https://www.wikitechy.com/html/img/table-within-a-table/table-with-in-table-smaple-code.png)
# Spanning ColumnS  :
## The colspan attribute in HTML specifies the number of columns a cell should span. It allows the single table cell to span the width of more than one cell or column. It provides the same functionality as “merge cell” in a spreadsheet program like Excel.
## Usage: It can be used with <td> and <th> element while creating an HTML Table.
## Attribute Values: It contains a value i.e number Which specify the number of columns that a cell should span. 

## <td>: The colspan attribute when used with <td> tag determines the number of standard cells it should span. 


# Spanning Rows
## The rowspan attribute in HTML specifies the number of rows a cell should span. That is if a row spans two rows, it means it will take up the space of two rows in that table. It allows the single table cell to span the height of more than one cell or row. It provides the same functionality as “merge cell” in the spreadsheet program like Excel.
## Usage: It can be used with <td> and <th> element in an HTML Table.
 

## Attribute Values: It contains a value i.e number Which specify the number of rows that a table cell should span. 

## <td>: The rowspan attribute when used with <td> tag determines the number of standard cells it should span. 
# Functions, Methods, and Objects :
## JS Functions Are Objects
## Yes, in JS world a function is considered an object, and to explain the reason why we will have to learn about types. Types in JavaScript are categorized by:

## Primitives (string, number, null, boolean, undefined, symbol): these are immutable data types. They are not objects, don’t have methods and they are stored in memory by value.
## Non-Primitives (functions, arrays and objects): these are mutable data types. They are objects and they are stored in memory by reference.
## ![](https://miro.medium.com/max/1400/1*SPZnQAWqfvZSCz4Y4rzyzg.png)
## JavaScript Methods
## JavaScript methods are actions that can be performed on objects.
## You will typically describe fullName() as a method of the person object, and fullName as a property.

## The fullName property will execute (as a function) when it is invoked with ().

## This example accesses the fullName() method of a person object:
## Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life. The concept of objects in JavaScript can be understood with real life, tangible objects.

## In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.
## A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:
## Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive. You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year as follows:

## var myCar = new Object();
## The above example could also be written using an object initializer, which is a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}):
## An object property name can be any valid JavaScript string, or anything that can be converted to a string, including the empty string. However, any property name that is not a valid JavaScript identifier (for example, a property name that has a space or a hyphen, or that starts with a number) can only be accessed using the square bracket notation. This notation is also very useful when property names are to be dynamically determined (when the property name is not determined until runtime). Examples are as follows:
## Please note that all keys in the square bracket notation are converted to string unless they're Symbols, since JavaScript object property names (keys) can only be strings or Symbols (at some point, private names will also be added as the class fields proposal progresses, but you won't use them with [] form). For example, in the above code, when the key obj is added to the myObj, JavaScript will call the obj.toString() method, and use this result string as the new key.
## You can use the bracket notation with for...in to iterate over all the enumerable properties of an object. To illustrate how this works, the following function displays the properties of the object when you pass the object and the object's name as arguments to the function
## Starting with ECMAScript 5, there are three native ways to list/traverse object properties:

## for...in loops
## This method traverses all enumerable properties of an object and its prototype chain.
## Object.keys(o)
## This method returns an array with all the own (not in the prototype chain) enumerable properties' names ("keys") of an object o.
## Object.getOwnPropertyNames(o)
## This method returns an array containing all own properties' names (enumerable or not) of an object o.

