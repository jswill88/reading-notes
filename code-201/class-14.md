# CSS Transforns, Transitions, and Animations

## CSS Transforms
* Transform syntax includes the type and a specific number `transform: scale(1.5);`
* You can rotate by a specific amount of degrees `transform: rotate(45deg)`
* You can make an element bigger with `transform: scale(.8)`, which would make something 80% of the original
* You can scale x or y with `scaleX` or you can have a specific value for both with `scale(x,y)`
* translate moves the object accross and x or y axis, or both with (x,y) notation
* You can skew an element with `skew(5deg,7deg)`. You can choose `skewX` or `skewY` also.
* You can make an element look like it is leaning over with  `perspective`, which takes a depth(px) and a deg
* You can rotateY 180deg to see an element backwards

## Transitions and Animations
* To make a transition, put `transition-property`, `transition-duration`, and `transition-timing-function` in the css element with the original state
* Not all properties can be transitioned, only those that have a halfway point
* Use commas to separate multiple things you want to transform:
```
transition-property: background-color, border-radius;
transition-property: .2s,1s;
```
* You can set a transition-delay property
* You can use all three properites on one line with `transition:`
* Make backface-visibility hidden to put a different image on the backside of an element
* Use @keyframes to make animations
* Set the animation-name and animation-duration in the element you wnat to animate, then make the @keyframes

## 8 Simple CSS3 transitions
* Use transform to make an object grow or shrink
* Rotate an object by specifying the amount of degrees
* Turn a square to a circle by changing the border-radius
* Make an object swing by having the element transform back and forth with @keyframes
* Add an inset border with box-shadow

## 6 Buttons animated
* This shows you can have something animated, then stop when you hover
* You can make different animations start and stop based on which button you press
* This shows the capabilities of transitions, transform, and animation

## Keyframes
* This shows how you can make a ball look like it is bouncing using keyframes.
* If you have to go to a similar over and over, you can set the same position for multiple keyframe percentage points

## 404
* This shows how to use an infinitely looping animation
* Using percentages, they are able to make the numbers look like they are coming closer and going further away

## Pure CSS Boune Animation
* This makes the border width 50% then adjusts the height and width of the circle to make it look like a bouncing ball on the screen
* This also uses the animation-timing-function ease-out to make an interesting effect.