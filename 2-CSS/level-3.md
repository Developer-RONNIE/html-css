<h1 align="center"> level-3 🚀</h1>

## Units in CSS
### Relative
- ```%``` - Relative to the size of the parent element
- ```em``` - Relative to the font size of the current element
- ```rem``` - Relative to the font size of the root element
## Percentage (%)
It is often used to define a size as relative to an element's parent object.
```
width : 33% ;

margin-left : 50% ;
```

## Em & Rem (Root Em)
| Unit | Relative to | 
|--------------- | --------------------------------------------------------------------------------------------------------------------|
| em | Font size of the parent, in the case of typographical properties like font-size, and font size of the element itself, in the case of other properties like width. |
| rem | Font size of the root element (usually ```html```) |

## Others
```
vh: relative to 1% viewport height

vw : relative to 1% viewport width
```

- ```vh``` (Viewport Height): Represents 1% of the height of the browser window.
- ```vw``` (Viewport Width): Represents 1% of the width of the browser window.

## Position
The position CSS property sets how an element is positioned in a document.
```
position : static / relative / absolute / fixed 
```
- ```static``` - default position (The top, right, bottom, left, and z-index properties have no effect)
- ```relative``` - element is relative to itself. (The top, right, bottom, left, and z-index will work)
- ```absolute``` - positioned relative to its closest positioned ancestor. (removed from the flow)
- ```fixed ```- positioned relative to browser. (removed from flow)
- ```sticky``` - positioned based on user's scroll position

## z-index
- It decides the stack level of elements
- Overlapping elements with a larger z-index cover those with a smaller one.

```
z-index : auto (0)

z-index : 1 / 2 / ...

z-index : -1 / -2 / ...
```

## Background Image
Used to set an image as background 
```
background-image : url("image.jpeg");
```

## Background Size
```
background-size : cover / contain / auto
```

- ```background-size: cover;``` : Scales the background image to completely cover the container element, even if it means cropping parts of the image.
- ```background-size: contain;``` : Scales the background image to fit within the container element without cropping any part of the image.
- ```background-size: auto;``` : The default value. The image is displayed at its original size. If the image is larger than the container, it will be clipped.

## Practice Set 5

### Qs: 
Create the following layout using the given html.
- Give the div a height, width & some background image. 
- Use the appropriate position property for the div element to place it at the right end of the page. (The div should not move even on scroll)
- Use z-index to place the div on top of page.

```
<p> lorem*5 </p>
<div> Love Nature </div>
<p> lorem*5 </p>
```