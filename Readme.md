# Lesson 1 - Declarations/Variables

- link https://popcode.org/?snapshot=db2bfccb-e2cc-4702-a062-c0a6d4fedbfb

# Lesson 2 - Data structures and types
- link https://popcode.org/?snapshot=80db0a78-2c58-48ae-a8a6-c8906edf37f1

# Lesson 3 - Control flow/Expression and Operators
- link https://popcode.org/?snapshot=e8e54afa-6c29-435c-92df-87285a8e5542

# lesson 4 - Basic HTML
- link [https://popcode.org/?snapshot=c749ecd2-1199-4ad4-a2ed-7eade35c455d](https://popcode.org/?snapshot=c749ecd2-1199-4ad4-a2ed-7eade35c455d)

# lesson 5 - Basic css
- link [https://popcode.org/?snapshot=093f1f10-313d-4faf-bf91-286edbeb2b14](https://popcode.org/?snapshot=093f1f10-313d-4faf-bf91-286edbeb2b14)

# lesson 6 - Advance
- link [https://popcode.org/?snapshot=123aa359-8d12-4fdc-9ac0-380bc1b13b09](https://popcode.org/?snapshot=c55058bb-7c39-4fcb-abc8-8f09e0de2c8e)


# Lesson 4 - Basic HTML


## What is HTML?
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.



### This is what basic html looks like

```
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>Welcome</h1>    
    </body>
</html>
```

### Activity #1

1. Copy and paste the code block above into the html window on the right.

1. Change the word `Welcome` to your name and see what happens 

1. Change the words `Page Title` to anything you like and see what happens


## What is an HTML Element?
- An HTML element is defined by a start tag, some content, and an end tag:

```
<tagname> 
  Content goes here... 
</tagname>
```
The HTML element is everything from the start tag to the end tag:

```
  <p>My first paragraph.</p>
```


### Activity #2

1. Copy and paste the code block below inside the `<body>` tags in the html window.

```
<p>This is a nice picture</p>
<button>Click Me!</button><input placeholder="hello"/>
<img src="https://cdn.pixabay.com/photo/2014/02/27/16/10/flowers-276014_1280.jpg">

```

### Activity #3 - Lets see what you can make

Types of tags:
- [list of the top 20 html tags](https://www.journaldev.com/55918/fundamental-html-tags)

1. click on the link above. 
1. use a couple of the tags from [this link](https://www.journaldev.com/55918/fundamental-html-tags) to see what you can build.

`hint: some of the tags will fail. Try to find ones that works`





# Lesson 5 - Basic CSS 


## What is CSS for?
CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.



### This is what basic css looks like. 
- CSS is A rules based language. This means that you are defining a set of rules to tell how an object must behave.

```
h1{
 color: blue;   
}

p{
 color: red;   
}

.classinput{
    background: red;
    height: 40px;
    padding: 10px;
} 
```

- The first section of a CSS block is the selector. It is used to tell which html object(s) the specified rules should apply to. 
- The second section of a CSS block is the rules. 

```
h1{
 color: blue;   
}
```
- The code above is saying, find all the `h1` tags and change there color to blue.

### Activity #1

1. Copy and paste the h1 code block above into the css window on the right and note what happens.


## Using a class selector in CSS

- A class selector is almost the same as a tag selector. The only difference is we put a **.** followed by the class name to be selected. 

example:
```
.cls{
   color:red;
}
```
### Activity #2

1. Copy and paste the example code block above into the css window on the right and note what happens.

1 Try to change the color of the word `Class` to green.


## Using a id selector in CSS

- An id selector is identical to the other two selectors except it uses `#` follow by the id of the object to be selected

example
```
#to{
  color: purple;
  font-family: Cursive;
    
}
```
### Activity #3

1. Copy and paste the example code block above into the css window on the right and note what happens.


## Applying CSS rules.
- Now that we know how to select and apply rules to html objects, let's see if we can apply some simple styles.

### Activity #4

1. Copy and paste the example code blocks below one by one and note what happens. Pay attention because you will be styling your own object next.

- Update the input container CSS
```
.classinput{
 	background: red;
    height: 40px;
    padding: 10px;
} 
```
- Update input button and input box CSS

```
.classinput button {
    height: 35px;
    color: green;
    
}

.classinput input {
    margin-top: 5px;
    height: 30px;
    margin-left: 10px;
} 
```

- Update input button and input box CSS outside of the input container.

```
.classbtn {
    height: 35px;
    margin: 10px;
    border-radius: 10px;
    background: green;  
}


.classinpt{
    height: 30px;
    margin: 10px; 
    border-radius: 10px;
    background: green;
    padding: 5px;
}
```
- Resize image to fix screen

```
.clsimg{
    height: 350px;
    width: 100%; 
}

.clsimg img{
    height: 100%;
     width: 100%; 
    
}
```

## How to make a website interactive. 

- We can use CSS and html events to make our site interactive. the syntax is similar to the base selector syntax. the only difference is we add the html event to listen for to the selector.


example. - We want to change the color of the input container every time the mouse moves over it.

```
.classinput:hover {
 	background: green;
} 

```

### Activity #5

1. Copy and paste the example code block above into the css window on the right and note what happens.


### Activity #6

1. Add some styles to the button and text box without styles. copy and paste the below code blocks into the CSS window on the right and add your own styling.  Have fun! 

```
.classinpttst{
/*  add some styles here */
    
}

.classbtntst{
/*  add some styles here */
}
```
