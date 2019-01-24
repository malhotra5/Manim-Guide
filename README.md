# Manim-Guide
A documentation of the most common Manim functionalities such as classes and methods. 

## Start
If you have completed the tutorial, then congrates. This will be a guide for you if you ever forget some of the animations, methods, etc. 

If you want to check out the tutorial, visit this link 

[Manim Tutorial](https://github.com/malhotra5/Manim-Tutorial)

This guide will show you the most common methods, classes, etc and as well as the arguments you should pass through. 

The guide gives a description on the functionalities and how to pass parameters. 

## Table of Content
* Running Args
* Creations
* Animations
* Indication
* Movement
* Rotation
* Transformations
* Continuous Animations

**Running Args**
* -r hxw
This defines pixel resolution you want the video to be. More the resolution, more the time it will take to make the video. 
* -p
This tell Manim to show the result of the video after making it.
* -l
It is a predefined resolution. It is mainly used when making a new video, because it takes the least time to render.
* -m
A predefined resolution that looks good, and takes a considerable amount of time to make videos. 

**Creations:**
* ShowPartial
* ShowCreation
```
* Uncreate(Mobject, Mobject, ...)
Description: Removes mobject from screen while animating. Takes multiple mobjects as parameters.
```
* DrawBordersThenFill
* ``` Write(TextMobject)
```Description: Writes the text from left to right. Takes only one TextMobject as parameter.  ```

**Animations:**
* FadeOut(mobject)
* FadeIn(mobject)
* FadeInAndShiftFromDirection
* FadeInFrom
* FadeInFromDown
* FadeOutAndShift
* FadeOutAndShiftDown
* VFadeIn(VGroup)
* VFadeOut(VGroup)
* GrowFromPoint
* GrowFromCenter
* GrowFromEdge
* SpinInFromNothing
* ShrinkToCenter

**Indication:**
* FocusOn
* Indicate
* CircleIndicate
* ShowPassingFlash
* ShowCreationThenDestruction
* ApplyWave
* WiggleOutThenIn
* Vibrate
* TurnInsideOut

**Movement:** 
* MoveAlongPath(GraphFunction)

**Rotation:**
* Rotate

**Transformations:**
* Transform
* ReplacementTransform
* TransformFromCopy
* ClockwiseTransform
* CounterclockwiseTransform
* MoveToTarget
* ApplyMethod
* FadeToColor

**Continuous Animations:**
* ContinualRotation
* ContinualMovement

**Grouping**
* VGroup(Mobject, Mobject, ...)

