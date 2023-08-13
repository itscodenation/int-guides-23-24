# CSS Guide

A comprehensive guide for CSS, including syntax, properties and values, layouts, box model, and flexbox.

## Table of Contents
1. [CSS Syntax](#css-syntax)
2. [CSS Properties and Values](#css-properties-values)
3. [CSS Layout](#css-layout)
   - [Box Model](#box-model)
4. [CSS Flexbox](#css-flexbox)

## CSS Syntax <a name="css-syntax"></a>

CSS rules are made up of three components:

1. **Selector:** Identifies the parts of your page that will be affected by the rule. You can select using the tag name, id, or class.
2. **Property:** What you want to change for the selected elements, followed by a colon `:`.
3. **Value:** The value you want to set for the property, followed by a semicolon `;`.

```css
img {
 height: 30px;
 border: 1px solid red;
}
```

## CSS Properties and Values <a name="css-properties-values"></a>

Various CSS properties and their corresponding values, with examples and explanations:

### Text
```css
font-family: "Comic Sans";
font-size: 12px;
text-align: center;
color: blue;
```
- Changes the font to Comic Sans
- Changes font size to 12 pixels
- Aligns text to center
- Changes font color to blue

### Color
```css
background-color: #000000;
color: yellow;
```
- Changes background color to hex code `#000000`, which is black
- Changes font color to yellow

### Background
```css
background-color: pink;
background: url("ex.png");
```
- Changes background color to pink
- Changes background to an image with URL `"ex.png"`

### Size
```css
width: 50px;
width: 50%;
font-size: 20px;
```
- Changes width to 50 pixels
- Changes width to 50% of the screen
- Changes font size to 20 pixels

### Display
```css
display: none;
display: block;
```
- `none` hides the content
- `block` shows the content (default)

[Click here for more CSS selectors and tricks, in pxleyes.com's CSS Cheat Sheet](http://www.pxleyes.com)

## CSS Layout <a name="css-layout"></a>

### CSS Box Model <a name="box-model"></a>

All HTML elements are shaped like boxes with content, padding, border, and margin.

#### Content
- Any HTML element (paragraph, image, link, etc.). This is not a property.

#### Padding
- Spacing between the content and border
```css
padding: 20px;
padding-left: 100px;
```

#### Border
- Surrounds the padding
```css
border: 2px solid red;
border-right: 10px solid black;
```

#### Margin
- Spacing between the border of this element and the start of another
```css
margin: 15px;
margin-top: 25px;
```

## CSS Flexbox <a name="css-flexbox"></a>

Flexbox is a layout model that allows items within a container to be dynamically arranged.

```css
.container {
  display: flex;
}
```
Use the `justify-content` property to align child elements:
- `flex-start`: Aligns to the start
- `center`: Aligns to the center
- `flex-end`: Aligns to the end
- `space-between`: Spaces between elements
- `space-around`: Spaces around elements

```css
.container {
  display: flex;
  justify-content: space-between;
}
```
