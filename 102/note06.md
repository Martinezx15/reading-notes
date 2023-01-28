# **What is JavaScript?** 
JavaScript, often abbreviated as JS, is a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS. As of 2022, 98% of websites use JavaScript on the client side for webpage behavior, often incorporating third-party libraries
## **A high-level definition**
JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.
HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)
The three layers build on top of one another nicely. Let's take a simple text label as an example. We can mark it up using HTML to give it structure and purpose:

## **So what can it really do?**  
The core client-side JavaScript language consists of some common programming features that allow you to do things like:
Store useful values inside variables. In the above example for instance, we ask for a new name to be entered then store that name in a variable called name.
Operations on pieces of text (known as "strings" in programming). In the above example we take the string "Player 1: " and join it to the name variable to create the complete text label, e.g. "Player 1: Chris".
Running code in response to certain events occurring on a web page. We used a click event in our example above to detect when the label is clicked and then run the code that updates the text label.
And much more!

## **JavaScript running order**
When the browser encounters a block of JavaScript, it generally runs it in order, from top to bottom. This means that you need to be careful what order you put things in. For example, let's return to the block of JavaScript we saw in our first example:const para = document.querySelector('p'.
  
## **Editor or IDE**  
Any text editor can be used.
On MS Windows you can even use the built-in plain Notepad, but I'd recommend something more powerful. You can download Notepad++ which is very similar to Notepad, but with tons of extra features, or get Aptana Studio. The latter has a steeper learning curve, so you might want to start with the more simple tool.  
  
## **Embed or include**  
You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file. In most cases the latter is recommended, but for our first examples, in order to make the whole thing work in a single file, we'll embed the JavaScript code inside some HTML.  In order to do that we add the <script> opening and </script> closing tags. Between the two we write our JavaScript code.

## **Input Output**
The very first thing we need to learn is how to interact with the JavaScript code running in the browse. There are a number of way JavaScript can display text for the user (output). The most simple one is by using the alert function:
## **alert**
This will show a pop-up in the browser with the text. (You can click on Try! that will open the specific script in a separate window.) The alert() function is actually rarely used, but it is an easy way to show the use of JavaScript.
## **document.write**
This function was often used when one wanted to change what's shown. Today, there are some more advanced techniques.
## **console.log**
Finally let's see how developers usually print out debugging information.
In order to see the console you'll need to open it.
prompt The fist one is called prompt. It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function. Then, in this example we use the document.write method to update the html with the text.
## **confirm**
The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.Of course in order for this to make more sense you'll have to understand what true and false really mean and what this if - else construct does. If you have programming background then you probably already understand the code, and even if you don't have programming background you might figure out.
That code can basically be translated to the following English sentence:
If confirm returned true, print "Hello World", otherwise print "OK, I won't print it."
Or even better:

## **Things I want to know more about**
- Script loading strategies
- async and defer
- What went wrong? Troubleshooting JavaScrip

