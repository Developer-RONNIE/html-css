<h1 align="center"> level-2 🚀</h1>

## Box Model in CSS
- Height
- Width
- Border
- Padding
- Margin

## Height
- By default, it sets the content area ```height``` of the element

```
div {

height: 50px;

}
```


## Width
- By default, it sets the content area width of the element
```
div {

width: 50px;

}
```

## Border
- Used to set an element's border
```
border-width : 2px;
border-style : solid / dotted / dashed
border-color : black;
```

- Shorthand
```
border : 2px solid black;
```

- Used to round the corners of an element's outer border edge
```
border-radius : 10px;

Border

border-radius : 50%;
```

## Padding
- padding-left
- padding-right
- padding-top
- padding-bottom

- Shorthand
```
padding: 50px;
```

- top | right | bottom | left -> clockwise
```
padding: 1px 2px 3px 4px;
```

## Margin
- margin-right
- margin-left
- margin-top
- margin-bottom

- Shorthand
```
margin: 50px;
```

- top | right | bottom | left -> clockwise
```
margin: 1px 2px 3px 4px;
```

## Practice Set 3
### Q1:Create a div with height & width of 100px.
- Set its background color to green & the border radius to 50%.
### Q2: Create the following navbar.

<div align="center">
<img src="https://github.com/Developer-RONNIE/cloudvault/blob/main/public/assets/icons/git-banner.png" alt="Project Banner">
</div>

## Display Property

```
display: inline / block / inline-block / none
```

- `````inline``` - Takes only the space required by the element. (no margin/ padding)
- ```block``` - Takes full space available in width.
- ```inline-block``` - Similar to inline but we can set margin & padding.
- ```none``` - To remove element from document flow.


## Visibility

```
visibility: hidden;
```
**NOTE** : When visibility is set to none, space for the element is reserved. But for display set to none, no space is reserved or blocked for the element.

## Alpha Channel
- RGBA - the ```fourth value``` (0.5) represents the ```alpha channel```, which controls the opacity of the color, where 0 is fully transparent and 1 is fully opaque.

```
color: rgba(255, 0, 0, 0.5);

color: rgba(255, 0, 0, 1);
```

## Practice Set 4


### Q1: 
- Create a webpage layout with a header, a footer & a content area containing 3 divs.
- Set the height & width of divs to 100px. (add the previous navbar in the header)

### Q2: 
- Add borders to all the divs.

### Q3: 
- Add a different background color to each div with an opacity of 0.5


### Q4: 
- Give the content area an appropriate height.

