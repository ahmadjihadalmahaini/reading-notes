# read03
# HTML Ordered Lists
## Ordered HTML List
## An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

## The list items will be marked with numbers by default:

## Example:
## <ol>
 ##  <li>Coffee</li>
  ## <li>Tea</li>
  ## <li>Milk</li>
## </ol>
## Ordered HTML List - The Type Attribute
## The type attribute of the <ol> tag, defines the type of the list item marker:
# ![](https://i2.wp.com/blog.thejaytray.com/wp-content/uploads/2015/04/005-Music-HTML-List-Code-Ordered-List.png)
## Definition Lists:
## Working with HTML Lists
## HTML lists are used to present list of information in well formed and semantic way. There are three different types of list in HTML and each one has a specific purpose and meaning.

## Unordered list — Used to create a list of related items, in no particular order.
## Ordered list — Used to create a list of related items, in a specific order.
## Description list — Used to create a list of terms and their descriptions.
## HTML Unordered Lists
## An unordered list created using the <ul> element, and each list item starts with the <li> element.
## HTML Ordered Lists
## An ordered list created using the <ol> element, and each list item starts with the <li> element. Ordered lists are used when the order of the list's items is important.
## A description list is a list of items with a description or definition of each item.
# ![](https://www.dummies.com/wp-content/uploads/412164.image0.jpg)
## The description list is created using <dl> element. The <dl> element is used in conjunction with the <dt> element which specify a term, and the <dd> element which specify the term's definition.

## Browsers usually render the definition lists by placing the terms and definitions in separate lines, where the term's definitions are slightly indented.
## HTML list advantages
## Flexibility: If you have to change the order of the list items in an ordered list, you simply move around the list item elements; when the browser renders the list, it will be properly ordered.
## Styling: Using an HTML list allows you to style the list properly using CSS. The list item tags <li> are different from the other tags in your document, so you can specifically target CSS rules to them.
## Semantics: HTML lists give the content the proper semantic structure. This has important benefits, such as allowing screen readers to tell users with visual impairments that they are reading a list, rather than just reading out a confusing jumble of text and numbers.
## To put it another way, don’t code list items using regular text tags. Using text instead of a list makes more work for you and can create problems for your document’s readers. So if your document needs a list, you should use the correct HTML list format.

# Boxes :
## The CSS Box Model
 ## In CSS, the term "box model" is used when talking about design and layout.

## The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
## Explanation of the different parts:

## Content - The content of the box, where text and images appear
## Padding - Clears an area around the content. The padding is transparent
## Border - A border that goes around the padding and content
## Margin - Clears an area outside the border. The margin is transparent
## The box model allows us to add a border around elements, and to define space between elements.
# ![](https://front-end-interview.com/wp-content/uploads/2021/01/css-box-model.jpg)
# CSS Box Sizing
## Without the CSS box-sizing Property
## By default, the width and height of an element is calculated like this:

## width + padding + border = actual width of an element
height + padding + border = actual height of an element

## This means: When you set the width/height of an element, the element often appears bigger than you have set (because the element's border and padding are added to the element's specified width/height).
## With the CSS box-sizing Property
## The box-sizing property allows us to include the padding and border in an element's total width and height.

## If you set box-sizing: border-box; on an element, padding and border are included in the width and height:
# ![](https://i.stack.imgur.com/ZU6S3.png)
# Basic JavaScript Instructions
## JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.
## What is JavaScript?
## JavaScript ("JS" for short) is a full-fledged dynamic programming language that can add interactivity to a website. It was invented by Brendan Eich (co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation).

## JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!

## JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:

## Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
## Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
## Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.
## It's outside the scope of this article—as a light introduction to JavaScript—to present the details of how the core JavaScript language is different from the tools listed above. You can learn more in MDN's JavaScript learning area, as well as in other parts of MDN.
# Language basics crash course
## To give you a better understanding of how JavaScript works, let's explain some of the core features of the language. It's worth noting that these features are common to all programming languages. If you master these fundamentals, you have a head start on coding in other languages too!
# ![](https://www.tutorialrepublic.com/lib/images/javascript-illustration.png)
# Decision Making in Java (if, if-else, switch, break, continue, jump)
## Decision Making in programming is similar to decision making in real life. In programming also we face some situations where we want a certain block of code to be executed when some condition is fulfilled.
## A programming language uses control statements to control the flow of execution of program based on certain conditions. These  are used to cause the flow of execution to advance and branch based on changes to the state of a program.
## Java’s Selection statements:

## if
## if-else
## nested-if
## if-else-if
## switch-case
## jump – break, continue, return
## These statements allow you to control the flow of your program’s execution based upon conditions known only during run time.
# if: if statement is the most simple decision making statement. It is used to decide whether a certain statement or block of statements will be executed or not i.e if a certain condition is true then a block of statement is executed otherwise not.
## Here, condition after evaluation will be either true or false. if statement accepts boolean values – if the value is true then it will execute the block of statements under it.
## If we do not provide the curly braces ‘{‘ and ‘}’ after if( condition ) then by default if statement will consider the immediate one statement to be inside its block. For example,
# ![](https://media.geeksforgeeks.org/wp-content/uploads/if.png)
