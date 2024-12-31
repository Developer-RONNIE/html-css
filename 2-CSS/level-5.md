<h1 align="center"> level-5 🚀</h1>



## Transitions
Transitions enable you to define the transition between two states of an element.

- ```transition-property``` : property you want to transition (font-size, width etc.)
- ```transition-duration``` : 2s / 4ms ..
- ```transition-timing-function``` : ease-in / ease-out / linear / steps ..
- ```transition-delay``` : 2s / 4ms ..

## Transition Shorthand
property name | duration | timing-function | delay
```
transition: font-size 2s ease-in-out 0.2s;
```
## CSS Transform
Used to apply 2D & 3D transformations to an element

- rotate
```
transform: rotate(45deg);
```
Applies a 45-degree clockwise rotation to the element

- scale 
Uniformly resizes elements by scaling them along the X, Y, and optionally Z axes, to its original size in both width and height .
```
transform: scale(2);
transform: scale(0.5);
transform: scale(1, 2);
```


```
transform: scaleX(0.5);
transform: scaleY(0.5);
```
```transform: scaleX(0.5);```: Scales the element horizontally to half its original width while maintaining its original height.
```transform: scaleY(0.5);```: Scales the element vertically to half its original height while maintaining its original width.

- translate
```
transform: translate(20px);
transform: translate(20px, 50px);
```
moves an element along the X and Y axes, with one value for horizontal movement and two values for both horizontal and vertical movement.


```
transform: translateX(20px);
transform: translateY(20px);
```
```transform: translateX(20px);```: Moves the element 20 pixels to the right along the X-axis.
```transform: translateY(20px);```: Moves the element 20 pixels downwards along the Y-axis.

- skew
```
transform: skew (30deg);
```
Skews the element 30 degrees along the X-axis, creating a slanting effect.**

## Animation
To animate CSS elements

```
@keyframes myName {
  from { 
    font-size: 20px; 
  }
  to { 
    font-size: 40px; 
  }
}
```
```@keyframes myName { ... }```: This line declares the start of the ```keyframe animation block``` named "myName".
```from { ... }```: This block defines the ```starting state``` of the animation. In this case, the ```font-size``` of the ```element``` is initially ```20px```.
```to { ... }```: This block defines the ```ending state``` of the animation. In this case, the ```font-size``` of the ```element``` increases to ```40px```.

## Animation Properties
```
animation-name

animation-duration

animation-timing-function

animation-delay

animation-iteration-count

animation-direction
```

- ```animation-name: myAnimation;```: Specifies the name of the keyframe animation to apply to the element. This name must match the name defined in the @keyframes rule.

- ```animation-duration: 2s;```: Sets the total time it takes for the animation to complete one cycle. In this case, it's 2 seconds.

- ```animation-timing-function```: ease-in-out;: Controls how the animation's speed changes over time.

ease-in-out: The animation starts slowly, accelerates, then slows down again at the end. Other options include linear, ease-in, ease-out, cubic-bezier(), and more.

- ```animation-delay: 1s;```: Specifies the time delay before the animation starts. In this example, the animation will begin 1 second after the page loads or the element becomes visible.

- ```animation-iteration-count: 3;```: Determines how many times the animation should repeat.

3: The animation will play three times.
infinite: The animation will repeat indefinitely.

- ```animation-direction: alternate;```: Controls the direction of the animation playback.

alternate: The animation plays forwards on the first iteration and then backwards on the second iteration, and so on.


## Animation Shorthand
animation : myName 2s linear 3s infinite normal

## % in Animation
@keyframe myName {
0% { font-size : 20px; }
50% { font-size : 30px; }
100% { font-size : 40px; }
}
## Practice Set 8

### Qs: Create a simple loader using CSS


- Step1 : create a div with circular shape & a thick border from one end
(top/bottom/left/right)

- Step2 : To make it spin create an animation which transforms it from 0deg to 360deg

- Step3 : Add the animation property to the loader with infinite duration