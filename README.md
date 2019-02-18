
# Animate.css onScroll
This uses Dan Eden's [Animate.css](http://daneden.github.io/animate.css/) combined with scroll and touch events to animate any element.

## Installation
Add styles in `<head>`:
```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css" />
```
Add script right before closing `</body>` tag and after `jQuery`:
```html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="dist/animate.css.onscroll.min.js"></script>
```
Done 😀

## Usage
Set animation using  `data-animate`  attribute:
```html
  <div data-animate="fadeIn"></div>
```
[See full list of all animations](#animations)

And adjust behaviour by using `data-animate-*` attributes:
```html
  <div
    data-animate="bounceIn"
    data-animate-offset="50"
    data-animate-delay="100"
    data-animate-duration="2000"
    data-animate-once="true"
  >
  </div>
```
[See full list of default values](#defaults)

## Animations
**Attention Seekers**
 - bounce
 - flash
 - pulse
 - rubberBand
 - shake
 - swing
 - tada
 - wobble
 - jello
 - heartBeat

**Bouncing Entrances**
 - bounceIn
 - bounceInDown
 - bounceInLeft
 - bounceInRight
 - bounceInUp

**Bouncing Exits**
 - bounceOut
 - bounceOutDown
 - bounceOutLeft
 - bounceOutRight
 - bounceOutUp

**Fading Entrances**
 - fadeIn
 - fadeInDown
 - fadeInDownBig
 - fadeInLeft
 - fadeInLeftBig
 - fadeInRight
 - fadeInRightBig
 - fadeInUp
 - fadeInUpBig

**Fading Exits**
 - fadeOut
 - fadeOutDown
 - fadeOutDownBig
 - fadeOutLeft
 - fadeOutLeftBig
 - fadeOutRight
 - fadeOutRightBig
 - fadeOutUp
 - fadeOutUpBig

**Flippers**
 - flip
 - flipInX
 - flipInY
 - flipOutX
 - flipOutY

**Lightspeed**
 - lightSpeedIn
 - lightSpeedOut

**Rotating Entrances**
 - rotateIn
 - rotateInDownLeft
 - rotateInDownRight
 - rotateInUpLeft
 - rotateInUpRight

**Rotating Exits**
 - rotateOut
 - rotateOutDownLeft
 - rotateOutDownRight
 - rotateOutUpLeft
 - rotateOutUpRight

**Sliding Entrances**
 - slideInUp
 - slideInDown
 - slideInLeft
 - slideInRight

**Sliding Exits**
 - slideOutUp
 - slideOutDown
 - slideOutLeft
 - slideOutRight

**Zoom Entrances**
 - zoomIn
 - zoomInDown
 - zoomInLeft
 - zoomInRight
 - zoomInUp

**Zoom Exits**
 - zoomOut
 - zoomOutDown
 - zoomOutLeft
 - zoomOutRight
 - zoomOutUp

**Specials**
 - hinge
 - jackInTheBox
 - rollIn
 - rollOut

## Defaults

**Offset**
Number of pixels to scroll past before animation: *(default: 50)*
```html
<div data-animate-offset="50"></div>
```
**Delay**
Number of milliseconds to wait before animation: *(default: 0)*
```html
<div data-animate-delay="100"></div>
```
**Duration**
Length in milliseconds of animation: *(default: 1000)*
```html
<div data-animate-duration="1000"></div>
```
**Once**
Only run animation once: *(default: false)*
```html
<div data-animate-once="true"></div>
```
