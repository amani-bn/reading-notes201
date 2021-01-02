[](https://www.google.com/url?sa=i&url=https%3A%2F%2Fhtml.com%2F&psig=AOvVaw2x9iFv7UFqNAHeaw5Tt141&ust=1609705877681000&source=images&cd=vfe&ved=2ahUKEwjmqMPpi_7tAhV4BWMBHZOWCaEQjRx6BAgAEAc)
# html introduction
People access websites using software called *a web browser* such as chrome, Internet Explorer, Safari..
## Q: what is the Web servers?
A: special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them.
<hr>
  *Screen readers : programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.*

## Q: what is the Domain Name System (DNS)?
A: standard protocol that helps Internet users discover websites using human readable addresses,it associated various information with domain names assigned to each of the participatingentities . 
<hr>

# structure
## HTML stands to ==> HYPER TEXT MARKUP LANGUAGE.
### HTML pages are text documents.
# [structure was added to web page to make it easier to understand.]
The HTML code is made up of characters that live inside angled 
brackets — these are called HTML elements.
## Elements are usually made up of two tags:

1- an opening tag:denotes the start of a piece of content.

2- a closing tag: denotes the end.

### HTML uses elements  to describe the structure of pages.
### HTML uses tags to give the information they surround special meaning ,tags act like containers.
### Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

Everything inside ``<body>``is shown inside the main browser window.

``<head>`` contains information about the page & u find a ``<title>`` element inside it .
<hr>

# extra markup
**DOCTYPE tell a browser which version of HTML the page is using.**
## Q: How to add a comment to your code ?
A: add the text between these characters:``<!-- comment goes here -->``.

comments will make the code much easier to understand if you want return back to the code or  if someone else needs to look at the code .
## The id and class attributes allow you to identify particular elements.

It is important that no two elements on the same page have the same value for their id attributes.

# [The id attribute is known as a global attribute because it can be used on any element.]

class attribute:Its value should describe the class it belongs to,The class attribute on any element can share the same value.

## The ``<div>`` element allows you to group a set of elements together in one block-level box.

## The ``<span>`` element acts like an inline equivalent of the <div> element. It is used to either:
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
2. Contain a number of inline elements.
   
 ###  An iframe is like a little window that has been cut into your page — and in that window you can see another page.

### iframe stands to  inline frame.

## There are a few attributes that you will need to know to use iframe:
1-**src**: [The src attribute specifies the URL of the page to show in the frame]

2-**height** : [The height attribute specifies the height of the iframe in pixels]

3-**width** : [The width attribute specifies the width of the iframe in pixels]

## The ``<meta>``element lives inside the ``<head>`` element and contains information about that web page .It is not visible to users.

There are some characters that are used in and reserved by HTML code. 

Escape characters are used to include special characters in your pages such as <, >, and ©.
<hr>

# html layout
### HTML5 introduces a new set of elements that allow you to divide up the parts of a page. 


*Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements*.

## Here are New Html5 Layout Elements:
- The ``<nav>`` element is used to contain the major navigational blocks on the site such as the primary site navigation.
- The ``<article>`` element acts as a container for any section of a page that could stand alone and potentially be syndicated.
- The ``<aside>`` element has two purposes, depending on whether it is inside an ``<article>`` element or not.
  ### When the ``<aside>`` element is used inside an ``<article>`` element, it should contain information that is related to the article but not essential to its overall meaning.

### When the ``<aside>`` element is used outside of an ``<article>`` element, it acts as a container for content that is related to the entire page.
### The ``<section>`` element groups related content together, and typically each section would have its own heading.

### The purpose of the ``<hgroup>`` element is to group together a set of one or more ``<h1>`` through <h6> elements so that they are treated as one single heading. 

### ``<figure>`` element should also contain a ``<figcaption>`` element which provides a text decription for the content of the ``<figure>`` element.
###  ``<div>`` element will remain an important way to group together related elements.

# process and design
## when you are creating a new website you must determine :
- specify target audience.
- Why People Visit YOUR Website.
- What Your Visitors are Trying to Achieve.
- What Information Your Visitors Need  to achieve their goals quickly and effectively.
- How Often People Will Visit Your Site.
  
  **Site Maps** :  create a diagram of the pages that will be used to structure the site,  allow you to plan the structure of a site.

**wireframe** : a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

By creating a wireframe you can ensure that all of the information that needs to be on a page is included.

Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.

You can differentiate between pieces of information using size, color, and style. 

You can use grouping and similarity to help simplify the information you present.
<hr>

# java introduction
## JavaScript can be used in browsers to make websites more interactive, interesting, and user-friendly by :
- ACCESS CONTENT :You can use JavaScript to select any element, attribute, or text from an HTML page. 
- MODIFY CONTENT :You can use JavaScript to add elements, attributes, and text to the page, or remove them.

## traditional rules of programming for javascript :
- PROGRAM RULES : You can specify a set of steps for the browser to follow.
- REACT TO EVENTS : You can specify that a script should run when a specific event has occurred.
  
<hr>

# ABC of programming
## Q:What is a script?
A: a series of instructions that a computer can follow to achieve a goal. 

## To write a script:
-  DEFINE THE GOAL.
- DESIGN THE SCRIPT :To design a script you split the goal out into a series of tasks.
- CODE EACH STEP using programming language .

### Computers solve problems programmatically; they follow series of instructions, one after another.

### COMPUTERS CREATE MODELS OF THE WORLD USING DATA

### the model use objects to represent physical things.
# **object** can have :
- properties : tell us about the object .
- methods : perform tasks using the properties of that object .
- events : which are triggered when a user interacts with the computeer.

### **Properties** describe characteristics of the current web page. 

### **event** : the computer's way of sticking up its hand to say, "Hey, this just happened!

### **Methods** typically represent how people (or other things) interact with an object in the real world. 

### WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS.

### THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE.

## how a browser interprets the HTML code and applies styling to it:
- RECEIVE A PAGE AS HTML CODE.
- CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY.
- USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN.
  
## The **interpreter** takes your instructions and translates them into instructions the browser can use to achieve the tasks you want it to perform. 

## HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER :
- **CONTENT LAYER** (. html files) This is where the content of the page lives. The HTML gives the page structure and adds semantics. 
- **PRESENTATION LAYER** (. css file) the CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, etc.).
- **BEHAVIOR LAYER** (.js files) This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files.

### progressive enhancement :These three layers form the basis of a popular approach to building web pages .

<hr>

#### When you want to use JavaScript with a web page, you use the HTML ``<script>`` element to tell the browse  it is coming across a script. 
<hr>

#### The HTML ``<script>`` element is used to load the JavaScript file into the page. It has an attribute called src, whose value is the path to the script you created.  




 
 





















