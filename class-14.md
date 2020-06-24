# Read: 14a - CSS Transforms, Transitions, and Animations

## CSS TRANSFORMATION
the transform property can change the possition of elements .
the ways can be summerized in :
- position
- change elements
- size
they can be 2D or 3D
the look of it will be like :
```css
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
*2D Rotate*
```css
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```
notice its midured by degrees.
 *2D Scall*
 ```css
 .box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
```
this will change the apearant size and it can be on the x-y or both.

*translation*
```css
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}
translation can be measured in many scalls.
```
*skew*
```css
.box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}
will distort elements in the axes.
```
you can combine the properties.

### there are many others for 3D as well.

## ANIMATION
for a translation to take place you must use pseudo-classes.
```css
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```
this will change the colors in the duration and way determined.

using ```@keyframe``` rule you can animate the element to alter its state . note that you should change in one property only .  

```css
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```
this key frame now is declared , then you should assign it to an element .
```animation-nameL;```
you can define its duration too.

# Read: 14b - What Google Learned About Teams
- note that :psychological safety and emotional conversations were related
- it doesnt matter what are your skills as a leader , whats important is the ability to choose right.
-  Everything is different now, data reigns supreme, today’s winners deserve to triumph because they are cleareyed enough to discard yesterday’s conventional wisdoms and search out the disruptive and the new.
- it is eazy to gain data about how people behave, but difficult to find relations.
- an equally distributed talking is a key for good team conversation.
- the aim of these talks is to share and receave not being fancy .
