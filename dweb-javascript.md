# Dynamic web pages with Javascript
Javascript is a language written in plain text and can be written on any text editor. While HTML creates the structure of a web page, CSS creates the styling, Javascript creates the functionality.

The file is a *.js file* and is usually stored in it’s own root folder. An HTML page uses the **script** tag to recognize the code so it functions properly.

Javascript syntax is made up of the following:
- Statements
- Comments
- Variables
- Path TypesThese tags are a part of the functionality and interact with the web browser to create user interaction.

![alt text](images/jscript.jpg)

# My first time copying Javascript

var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
    greeting = 'Good evening!';
 } else if (hourNow > 12) {
 greeting = 'Good afternoon!';
} else if (hourNow > 0) {
 greeting = 'Good morning!';
} else {
    greeting = 'Welcome!';   
}
document.write('<h3>' + greeting + '</h3>');

[<== Back to Table of Contents](README.md)