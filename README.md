# gitTutorial
This is a tutorial to create a web page using html
to create a basic page we must first install the following:

INSTALL:-
>visual  studio code from the following link
https://code.visualstudio.com/download

<Once you download visualstudio create a folder on your desktop and update the folder in the visualstudio 
<Create a .html file in the folder and start with a simple display message.
refer for example below:
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
'
>once youre done typing the code run the program to view the output.
you can run the program by reveling it in the explorer or chrome

This is a simple HTML code. If you want to create web pages with designs and functions we can use styling.
The term styling gives rise to the use of CSS which means Cascading Style Sheets.
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

CSS can be added to HTML elements in 3 ways:

Inline - by using the style attribute in HTML elements.
<h1 style="color:blue;">This is a Blue Heading</h1>
Internal - by using a <style> element in the <head> section.
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

External - by using an external CSS file.
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
The most common way to add CSS, is to keep the styles in separate CSS files.
However, here we will use inline and internal styling, because this is easier to demonstrate, and easier for you to try it yourself.

CSS is the codes or simple syntaxes that we use to style our web pages or sheets.
They come with a set of simple codes and syntaxes which can be used to get the desired output. there are various ways and styling methods out of which css is one of the simplest forms and easily available.
few examples of CSS codes are listed below:

body {
  background-color: lightblue;
}  
:
used to change the background-color of any particular term

h1 {
  color: white;
  text-align: center;
}
:
aligns the text.

p {
  font-family: verdana;
  font-size: 20px;
}
: 
used to define the font-family and size.

This way we can create different kinds of styles for the web pages. we can also use animations .
CSS animations allows animation of most HTML elements without using JavaScript or Flash!
referlink to view animation:https://www.w3schools.com/css/css3_animations.asp.

we can also link pages from one to the other using href comment. this comment helps you refer to links or pages from one to the other.
for example:
<a href="https://www.w3schools.com">Visit W3Schools.com!</a>
Here if we click on the link it will redirect us to the page refered in the link.

For further tutorials and understanding visit "https://www.w3schools.com/html/default.asp" 




