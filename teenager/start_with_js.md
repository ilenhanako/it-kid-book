# JavaScript Getting Started

Let's start with a _reflection_.
We began with HTML page.
We made the page prettier, by putting `style`
More and more styles, mushrooming styles.
But it is not hygienic. So we plucked out all the styles, and put them in CSS file.
We replaced the `style` with simple `class`
So we get, a nice and clean page :heart:
But it is so boring. It is not moving, no animation, no business!
I want it more functional. When you click a button, it should shout or turn the page upside down.
This is where I need a JavaScript. Yay!:sparkles:



## Simple JavaScript Command
An example of a simple Javascript command.

```javascript
alert('how are you?')
```

_alert ?_ What is that? An alert is a pop up. _how are you?_ is a example name or quote that you want to show in your popup.
Try making your own pop up now!

## How to add JavaScript?
In HTML, the opening tag for HTML is '<html>' aand its closing tag is '</html>'
_RECALL: What is a tag? _

JavaScript commands are placed within `<script>` and `</script>`. In short, it is within script tag.
The above example(alert pop up) must be enclosed within `script tag`. 

## How to test?
- [ ] Use Console inside Google Chrome Developer toolbar
- [ ] Update directly the HTML code

## JavaScript function
When papa ask you to help for chores, he will command

1. sweep the floor
2. wash the cloth
3. fold your blanket
4. fold the clothes
5. bla bla bla (the list is too long)

But papa is so efficient, instead of saying out all those commands, he just said `do chores`, and kid is expected to do all these long list.
His efficiency is a learning from JavaScript function. Instead of typing all those command one by one, everytime it is needed ~ he wrote a JavaScript function and name it as `do_chores`. Anytime he want it to happen, he will `execute` by calling `do_chores()` 

### Sample of a JavaScript function 
``` javascript
 var changeColorToRed = function() {
  var xyz = $("#registrationForm")
  xyz.css("background-color","red");
 } 
```

### How to bind a button click to JavaScript function execution
When you press a button and after that you would want the page colour to change, please...  
 Type the following commands in your HTML page:
 
 ```html
 <a href="javascript:void(0)" class="btn" onclick="changeColorToRed()">A button label</a> 
 
 ```
 
 _A button label_ refers to the text that you would like your button to display. 

## jQuery
JavaScript and jQuery are brothers, similar to English and Singlish.
Is Singlish a form of English?
__Yes__

Similarly jQuery is also a form of JavaScript.

But, in Singlish, you know much more words, that does not exist in English, like `makan`, `kepo`, `yalor`, ... Those words are special and friendly. Singaporeans like to use it.

Similarly in jQuery, there are more commands that make JavaScript programmers happier.
E.g. in JavaScript we know this command
``` javascript
var email = document.getElementById("email_textbox");
```
In jQuery, we could achieve similar thing by
``` javascript
var email = $("#email_textbox");
```

One advantages of using jQuery is the commands are typically shorter. Another benefit, jQuery commands can be used across different browsers while some JavaScript commands can be used only in 1 browser and has a different command in another browser.



