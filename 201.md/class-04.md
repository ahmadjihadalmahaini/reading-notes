# read04
# 1- HTML:
##  HTML Links :
## What is a link?

## It is a connection from one web resource to another.A link has two ends,An anchor and direction. The link starts at the “source” anchor and points to the “destination” anchor, which may be any Web resource such as an image, a video clip, a sound bite, a program, an HTML document or an element within an HTML document.
## HTML Link Syntax

## Links are specified in HTML using the “a” tag.
# ![](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-08-at-12.17.21-AM.png)
## Syntax Explanation:

## href : The href attribute is used to specify 
## the destination address of the link used.
## Text link : The text link 
## is the visible part of the link.
## Internal Links

## An internal link is a type of hyperlink whose target or destination is a resource, such as an image or document, on the same website or domain.
## Input:

## <!DOCTYPE html>
## <html>
## <h3>Internal Link And External Link Example</h3>
## <body>
##<p><a href="html_contribute.asp/">GeeksforGeeks Contribute
## </a> It is a link to the contribute page on GeeksforGeeks' website.</p>
  
## <p><a href="https://www.geeksforgeeks.org">GeeksforGeeks
## </a> It is a link to the GeeksforGeeks website on the World Wide Web.</p>
  
## </body>
## </html>
## Different types of links appear in different formats such as:

## An unvisited link appears underlined and blue in colour by default.
## A visited link appears underlined and purple in colour by default.
## An active link appears underlined and red in colour by default.
## The appearances of links can be changed by using CSS.
# ![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)

# Linking to other Web Pages
## Linking in HTML code is done with the anchor tag, the <A> tag. The letter "A" in the tag is then followed by an attribute. For a link to another web page, the "A" is followed by "HREF". To set a bookmark in the same page, the "A" is followed by "NAME", which you'll see how to do later.

## Take a look at this example, which is a link to the popular search engine Google:

## <A HREF = "http://www.google.com/">Google Search Engine</A>
## Notice where all the angle brackets (< >) are in the link. After the first one, we have the "A" part of the tag. Then we have the HREF part, signifying a link to another web page. After that comes an equals sign (=). After the equals sign comes the address of the web page itself. The address is case sensitive, so if there is a capital letter in the address, make sure to include it. This address www.google.com is different from this address www.gOOgle.com.

## After the address comes the right angle bracket ( > ). Next comes the text that people see, the text you want them to click on. To close an anchor link, you use the end anchor tag. Which is this: </A>

## But let's get some practical work done.
#  email links html 

## It is not difficult to put an HTML email link on your webpage but it can cause unnecessary spamming problem for your email account. There are people, who can run programs to harvest these types of emails and later use them for spamming in various ways.

## You can have another option to facilitate people to send you emails. One option could be to use HTML forms to collect user data and then use PHP or CGI script to send an email.

## A simple example, check our Contact Us Form. We take user feedback using this form and then we are using one CGI program which is collecting this information and sending us email to the one given email ID.

## Note − You will learn about HTML Forms in HTML Forms and you will learn about CGI in our another tutorial Perl CGI Programming.

## HTML Email Tag
## HTML <a> tag provides you option to specify an email address to send an email. While using <a> tag as an email tag, you will use mailto: email address along with href attribute. Following is the syntax of using mailto instead of using http.

## <a href = "mailto: abc@example.com">Send Email</a>



# ![](https://dsl.manisaskincare.pw/img/171235.jpg)

# 2- js :

## JS Functions Are Objects:
## JavaScript Functions are Objects!
## in JS world a function is considered an object, and to explain the reason why we will have to learn about types. Types in JavaScript are categorized by:

## Primitives (string, number, null, boolean, undefined, symbol): these are immutable data types. They are not objects, don’t have methods and they are stored in memory by value.
## Non-Primitives (functions, arrays and objects): these are mutable data types. They are objects and they are stored in memory by reference.
## To learn more about primitive vs reference values, you can check out this article and our full course on the “tricky parts of JavaScript”.
## As you can see, functions are inside the non-primitive category, which means that when you define a function you are creating an object.
##  Let’s see it in Action!
## So let’s create a function and treat it like if we just created an object.
# ![](https://raw.githubusercontent.com/ATL-WDI-Curriculum/js-objects-and-json/master/images/object-property-method.jpg)

## Let’s assign a variable and log it:
## // Function declaration.
## function showFavoriteIceCream() {
  ## const favIceCream = 'chocolate';

  ## console.log(`My favorite ice cream is ${favIceCream}`);
}

## // Let's assign a property.
## showFavoriteIceCream.flavours = ['chocolate', 'vanilla', 'strawberry'];

## // Let's log the showFavoriteIceCream function.
## console.log(showFavoriteIceCream);

## // Log
## // { [Function: showFavoriteIceCream]
## // flavours: [ 'chocolate', 'vanilla', 'strawberry' ] } -> property assigned

## As you can see, the showFavoriteIceCream function besides performing an action, is also behaving as an object, we are able to assign properties and methods to it.
## The this Keyword
## In a function definition, this refers to the "owner" of the function.

## In the example above, this is the person object that "owns" the fullName function.

## In other words, this.firstName means the firstName property of this object.

## Read more about the this keyword at JS this Keyword.
## Function parameters
## Default parameters
## Default function parameters allow formal parameters to be initialized with default values if no value or undefined is passed. For more details, see default parameters.

## Rest parameters
## The rest parameter syntax allows representing an indefinite number of arguments as an array. For more details, see rest parameters.
# Method definition syntax
## Starting with ECMAScript 2015, you are able to define own methods in a shorter syntax, similar to the getters and setters. See method definitions for more information.
## Differences
## All do approximately the same thing, with a few subtle differences:

## There is a distinction between the function name and the variable the function is assigned to. The function name cannot be changed, while the variable the function is assigned to can be reassigned. The function name can be used only within the function's body. Attempting to use it outside the function's body results in an error (or undefined if the function name was previously declared via a var statement). For example:

## Determining whether a function exists
## You can determine whether a function exists by using the typeof operator. In the following example, a test is performed to determine if the window object has a property called noFunc that is a function. If so, it is used; otherwise, some other action is taken.
