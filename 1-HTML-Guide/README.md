# HTML Guide

A reference tool for learning and understanding the basic structure and elements of HTML.

## Table of Contents
1. [Basic Structure of an HTML Document](#basic-structure)
2. [HTML Elements](#html-elements)
3. [Common HTML Elements with Examples](#common-html-elements)
4. [Nesting and Indentation](#nesting-and-indentation)
5. [HTML Elements with Attributes](#html-attributes)
6. [Class and ID Attributes](#class-id-attributes)

## Basic Structure of an HTML Document <a name="basic-structure"></a>
HTML documents have the following basic structure:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <p>My first paragraph</p>
  </body>
</html>
```

## HTML Elements <a name="html-elements"></a>
An HTML element consists of:
- Opening Tag
- Content
- Closing Tag
```html
<p>This is a paragraph</p>
```

## Common HTML Elements with Examples <a name="common-html-elements"></a>
Here are some common HTML elements with code examples and their output.

### Paragraph
```html
<p></p>
<p>This is a paragraph.</p>
```

### Headings
```html
<h1></h1>
<h3></h3>
<h6></h6>
<h1>Heading level 1</h1>
...
<h6>Heading level 6</h6>
```

### Ordered List (numbers)
```html
<ol>
  <li>George Washington</li>
  <li>John Adams</li>
</ol>
```

### Unordered List (bullets)
```html
<ul>
  <li>George Washington</li>
  <li>John Adams</li>
</ul>
```

### Line Break (Self-closing)
```html
<br>
<br>
```

### Button
```html
<button></button>
<button>Click Me</button>
```

### Div
```html
<div></div>
<div>This is a div</div>
```

### Input (Self-closing)
```html
<input>
<input>
```

## Nesting and Indentation <a name="nesting-and-indentation"></a>
In coding, nesting is when you put one tag completely inside another tag's content. Indentation helps you organize your code and makes it more readable.

```html
<div>
  <h1>Weekday</h1>
  <p>Monday</p>
</div>
```

## HTML Elements with Attributes <a name="html-attributes"></a>
An attribute adds extra information to an HTML element.

### Image (Self-closing)
```html
<img src="https://imgur/cats.png">
<img alt="dog running" src="https://dogs.com/image.jpg" class="dog-pic">
```

### Link (anchor tag)
```html
<a href="https://www.google.com"> This is a link to Google</a>
<a href="https://www.youtube.com" target="_blank">YouTube popout</a>
```

### External Font
```html
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
h1 { font-family: 'Pacifico', serif; }
```

### Input with Placeholder (Self-closing)
```html
<input placeholder="type here">
```

## Class and ID Attributes <a name="class-id-attributes"></a>
Details about assigning and selecting classes and IDs.

```css
/* CSS class and id examples */
.my-class { text-align: right; }
#my-id { color: blue; }
```

---
