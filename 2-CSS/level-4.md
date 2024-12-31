<h1 align="center"> level-4 🚀</h1>

## Flexbox
### Flexible Box Layout
It is a one-dimensional layout method for arranging items in rows or columns.
 
## The Flex Model
A layout model that distributes space among child elements ```flex items``` within a parent element ```flex container``` along the main axis.

- ```Flex Item```: A child element within a flex container.
- ```Flex Container```: The parent element that contains and arranges flex items.
- ```Main Axis```: The primary axis along which flex items are arranged (default: row).
- ```Cross Axis```: The axis perpendicular to the main axis

[Read More](https://www.w3schools.com/css/css3_flexbox.asp)

## Flexbox Direction
It sets how flex items are placed in the flex container, along which axis and direction.
- ```flex-direction : row;``` : (default)  Items are arranged horizontally, from left to right
- ```flex-direction : row-reverse;``` : Items are arranged horizontally, from right to left
- ```flex-direction : column;``` :  Items are arranged vertically, from top to bottom.
- ```flex-direction : column-reverse;``` : Items are arranged vertically, from bottom to top.

## Flex Properties for Flex Item
1.  ```justify-content``` : alignment along the main axis.
```
flex-start / flex-end / centre / space-evenly 
```

2. ```flex-wrap``` : Determines how flex items are wrapped when they overflow the container.
```
nowrap / wrap / wrap-reverse
```

3. ```align-items``` : alignment along the ```cross axis```.

4. ```align-content``` : alignment of space ```between``` & ```around``` the content along ```cross-axis```

## Flex Properties for Flex Container
1. ```align-self``` : alignment of individual along the cross axis.

2. ```flex-grow``` : how much a flex item will grow relative to the rest of the flex items if
space is available

3. ```flex-shrink``` : how much a flex item will shrink relative to the rest of the flex items if
space is available

## Practice Set 6
### Qs: 1
Create a navbar with 4 options in the form of anchor tags inside list items.
Now, use flexbox to place them all spaced equally in a single line.

### Qs: 2
Use flexbox to center one div inside another div.

### Qs:3
Which has higher priority - align-items or align-self?

## Media Queries
Help create a responsive website

```
@media (width : 600px) {
    div {
        background-color : red;
    }
}
```
- ```@media (width : 600px) { ... }```: This media query applies the styles within the block when the width of the viewport is exactly 600 pixels.

```
@media (min-width : 600px) {
    div {
        background-color : red;
    }
}
```
- ```@media (min-width : 600px) { ... }```: This media query applies the styles within the block when the width of the viewport is greater than or equal to 600 pixels.


## Practice Set 7
### Qs: Add a media query to implement the following:
- the color of a div changes to green for viewport width less than 300px
- the color of a div changes to pink for width between 300px & 400px
- the color of a div changes to red for width between 400px & 600px
- the color of a div changes to blue for width above 600px