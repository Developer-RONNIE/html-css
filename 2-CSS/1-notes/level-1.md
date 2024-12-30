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
- RGB :
Red, Green, Blue color values represented as integers between 0 and 255
```
color: rgb(255, 0, 0);

color: rgb(0, 255, 0);
```
- Hex (Hexadecimal) : 
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
### Q1: 
- Create a simple div with an id "box". 
- Add some text content inside the div. 
- set is background color to blues 

### 02: 
- Create 3 headings with h1, h2 & h3. 
- Give them all a class "heading" & set color of "heading" to red.

### Q3: 
- Create a button & set its background color to :
- green using css stylesheet
- blue using ```<style>``` tag
- pink using inline style

## Text Properties
- text-align : Controls the horizontal alignment of text within an element 
```
text-align : left / right / center
```

- text-decoration : Adds decorative lines to text 
```
text-decoration : underline / overline / line-through
```

- font-weight : Sets the thickness or weight of the font 
```
font-weight : normal / bold / bolder / lighter

font-weight : 100-900
```

- font-family : Specifies the font family to be used for text 
```
font-family : arial

font-family : arial, roboto
```

- **Generic font families** : Generic font families are determined by font family properties
such as serifs-which are decorative strokes on the ends of letters— or cursive
strokes. The generic font family name will specify the attribute that all fonts within that
family share, like serif, sans-serif, or monospace.
Here is an overview of the generic font families found in many word processing programs
1. serif. serif ionis are tacitonial typeraces usine cha aclers that nave serits which
are small winged or flared ips extending off the tips of a letter. Serif fonts are typically
used in printed books, newspapers, and magaznes. Some popular serif fonts include
Timas New Roman. Garamond, Palatino, and Georoia.
2. Sans-Serif: Sans-sert fonts use characters without serits and are more commonly
seen in cigila formats. A sars-sert lont wil typicaly be the delault font nì digital word.
processing programs. Sans serif tonts include Mia, Meivelica, Veldania, Trebuchet
MS, and Gill Sans.
3. Cursive: Gunuve tonts use characters that have connectve strokes which owe the
tont a handwritten appearance. Gurse lores nolude Come sans Is, Mode Poenca.
Sanvito, and Zapf-Chancery
4. Fantasy: Fantasy lonts are styled tonts that sull maintan the characteristics of
non-cursive, traditional alphabet glyphs. Examples include Cottonwood, Critter, and
Aloha Geometrique.
5. Monospace: Fonts in the monosoace tont tamily have characters that are all the
same woln, orno text te coped anoe or a manual monospaced typewrier.
Examoles of monosaaced fonts include Courier New, Monaco, Lucida Console.

- **Specific font families**: Specific font families are specific fonts with different styles
within the one font family name, such as Arial, Times New Roman, and Tahoma.

## Units in CSS
- Absolute

- Pixels (px): An absolute unit representing a single pixel on the screen. <br>
96px = 1 inch
```
font-size: 2px;
```

## Text Properties
line-height : Controls the vertical spacing between lines of text
```
line-height : 2px

line-height : 3

line-height : normal
```
- ```line-height: 2px;```: Sets the line height to 2 pixels (very small).
- ```line-height: 3;```: Sets the line height to 3 times the font size.
- ```line-height: normal;```: Uses the browser's default line height.


- text-transform : Changes the case of the text within an element
```
text-tranform : uppercase / lowercase / capitalize / none
```
- ```uppercase```: Converts all letters to uppercase.
- ```lowercase```: Converts all letters to lowercase.
- ```capitalize```: Capitalizes the first letter of each word.
- ```none```: Leaves the text case unchanged.

## Practice Set 2
### Q1: 
Create a heading centred on the page with all of its text capitalized by default.

### Q2: 
Set the font family of all the content in the document to "Times New Roman".

### Q3:
Create one div inside another div.
Set id & text "outer" for the first one & "inner" for the second one.
Set the outer div text size to 25px & inner div text size to 10px.