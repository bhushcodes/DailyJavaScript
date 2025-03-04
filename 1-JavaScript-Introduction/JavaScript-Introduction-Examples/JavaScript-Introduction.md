# What is JavaScript?

JavaScript is a programming language of web technologies.

- It can update and change both HTML and CSS.  
- It can calculate, manipulate, and validate data.  
- It can react to events and trigger actions.  
- It can be used to create animations and games.  
- It can be used to create responsive and dynamic web pages.  

## Why Study JavaScript?

- JavaScript is the world's most popular programming language.  
- JavaScript is easy to learn.  
- JavaScript is easy to use.  
- JavaScript is easy to understand.  
- JavaScript is easy to write.  
- JavaScript is easy to read.  

## JavaScript Can Change HTML Content

One of many JavaScript HTML methods is `getElementById()`.

The example below "finds" an HTML element (with `id="demo"`), and changes the element content (`innerHTML`) to `"Hello JavaScript"`:

```javascript
document.getElementById("demo").innerHTML = "Hello JavaScript";
```

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/gbOmgYX)

JavaScript accepts both double and single quotes:

```javascript
document.getElementById('demo').innerHTML = 'Hello JavaScript';
```

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/jEOByOQ)

## JavaScript Can Change HTML Attribute Values

In this example, JavaScript changes the value of the `src` (source) attribute of an `<img>` tag:

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/PwopWZQ)

## JavaScript Can Change HTML Styles (CSS)

Changing the style of an HTML element is a variant of changing an HTML attribute:

```javascript
document.getElementById("demo").style.fontSize = "35px";
```

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/xbxqPLE)

## JavaScript Can Hide HTML Elements

Hiding HTML elements can be done by changing the display style:

```javascript
document.getElementById("demo").style.display = "none";
```

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/emYvepq)

## JavaScript Can Show HTML Elements

Showing hidden HTML elements can also be done by changing the display style:

```javascript
document.getElementById("demo").style.display = "block";
```

**Try it yourself:**  
[CodePen Link](https://codepen.io/bhushcodes/pen/JojWOXX)
