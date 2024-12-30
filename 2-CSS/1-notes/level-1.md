<h1 align="center"> Getting started with CSS 🚀</h1>

## What is CSS?
- **CSS** stands for **Cascading Style Sheet**
- It is a language that is used to describe the style of a document.

## Basic Syntax
Here if you observe closely 
```
h1 {
   color: red;
}
```
- ```h1``` is the selector. It targets all ```HTML elements``` with the tag name ```h1``` (heading level 1)
- ```color``` is the CSS ```property```. It determines the color of the selected elements.
- ```red``` is the ```value``` assigned to the property. It specifies the desired color for the "h1" elements.


## Including Style
### Inline
``` 
<h1 style="color: red"> Apna College </h1>
```
- The style attribute is directly added to the HTML element ```<h1>```.
- The CSS property ```color``` and its value ```red```  are defined within the attribute's value, separated by a colon.
- This method is considered less maintainable and less scalable as it mixes CSS with HTML
### Style tag
```
<style>
    h1 {
        color : red;
    } 
</style>
```
- The CSS rules are placed within the ```<style>``` tag, which is typically located within the ```<head>``` section of the HTML document.
- This approach allows you to define styles for multiple elements within the same ```<style>``` block.
- It improves maintainability compared to inline styling as CSS is separated from the HTML content.
### External Stylesheet
Writing CSS in a separate document & linking it with HTML file
- CSS File (style.css):
```
h1 {
    color: red;
}
```
- HTML File (index.html):
```
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <h1> Apna College </h1>
</body>
</html>
```
- The CSS rules are written in a separate file (e.g., ```style.css```).
- The HTML document links to this external CSS file using the ```<link>``` tag in the ```<head>``` section.
- This is the most recommended approach for larger projects.
- It offers the highest level of maintainability, reusability, and separation of concerns between HTML and CSS.

## Color Property
Used to set the color of foreground
```
color: red;

color: pink;

color: blue;

color: green;
```

## Background Color Property
Used to set the color of background
```
background-color: red;

background-color: pink;

background-color: blue;

background-color: green;
```

## Color Systems
- RGB 
Red, Green, Blue color values represented as integers between 0 and 255
```
color: rgb(255, 0, 0);

color: rgb(0, 255, 0);
```
- Hex (Hexadecimal)
Hexadecimal color values represented as a six-digit code, each pair representing Red, Green, and Blue.
```
color: #ff0000;

color: #00ff00;
```
## Selectors
- Universal Selector : Selects all HTML elements on the page.
```
* { }
```
- Element Selector : Selects all HTML elements with the specified tag name (e.g., all ```<h1>``` headings).
```
h1 { }
```
- Id Selector : Selects a single element with the specified unique ID attribute
```
#myId { }
```
- Class Selector : Selects all elements with the specified class attribute
```
.myClass { }
```

## Practice Set 1
## Text Properties
## Units in CSS
## Text Properties
## Practice Set 2