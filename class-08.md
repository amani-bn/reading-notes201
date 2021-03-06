# LINKS 
![](https://weblog.west-wind.com/images/2019/Non-Navigating-Links-for-JavaScript-Handling/EmptyHref.png)
# Q: what is links ?
A: defining feature of the web because they allow you to move from one web page to another .

## Links are created using the ``<a>`` element , which has an attribute called href  .
# Q: what is s link text ?
A: The text between the opening ``<a>`` tag and closing ``</a>`` tag .
## When you link to a different website, the value of the href  absolute URL.

## You can create links to open email programs with an email address in the "to" field .

## When you are linking to other relative URL.

## <b>URL</b> stands for Uniform Resource Locator .
![](link.png)

<br/>

![](https://bashooka.com/wp-content/uploads/2018/12/javascript-grid-library-2.jpg)

# LAYOUT
##  CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline  box.
``<div>`` elements are often used as containing elements to group together sections of a page .

# Q : what is Containing Elements?
A : If one block-level element sits inside another block-level element then the outer box .

# Browsers display pages by position property which can be :
1- normal flow .
2- Relative positioning moves an element in relation to where it would have been in normal flow .
3- When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page .
4- Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed .

## When you use relative, fixed, or absolute positioning, boxes can overlap .

### If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page . 

### The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible .

## The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box .

# It can take the following values :
1-left:
The left-hand side of the box should not touch any other elements appearing in the same containing element .

 2-right:
The right-hand side of the box will not touch elements appearing in the same containing element .

3-both:
Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element .

4- none:
Elements can touch either side .

# The following three CSS properties are used to position the columns next to each other :
1- width:
This sets the width of the columns.

2- float:
This positions the columns next to each other.

3- margin:
This creates a gap between the columns.

## Resolution refers to the number of dots a screen shows per inch. 

## CSS frameworks aim to make your life easier by providing the code for common tasks.

## You can include multiple CSS files in one page .

<br/>

# FUNCTIONS

# Programmers use functions, methods, and objects to organize their code. 
# Q: WHAT IS A FUNCTION ?
A:a series of statements together to perform a specific task . 

![](data:image/png;base64,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)

### Functions can take parameters .
### may return a value. 

# HOW To create function :

1- use function keyword.

2- give it name .

3- write the stattements need to achieve task in {}.


### To call function by name of function .

# Q: WHAT IS AN OBJECT ? 

A: a set of variables and functions to create a model of a something you would recognize from the real world.
### If a variable is part of an object, it is called a property.

### If a function is part of an object, it is called a method. 


<br/>



![](https://images.ctfassets.net/k428n7s2pxlu/1aJnbCcUvAa4qiIg4kMeI/9c93dd78ff2c7c5ffbff3e14f5878a87/6-reasons-for-pair-programming.jpg)







