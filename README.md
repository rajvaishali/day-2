# day-2

blind 75 
 string question - maximum window substring



















 css 
  color : predefined color name  140 color
  RGB, RGBA,HEX,HSL,HSLA
  rgb(red,green,blue)
  0-255
  (0,0,0) black
  (255,255,255  ) white
  RGBA(red,green,blue,Alpha) aplha is for transparency range from 0.0 to 1.0 . 
  HEX  #rrggbb (00 to ff)
  #ff0000 - red, #000000 black , #ffffff white.
  hsl(hue,saturation,lightness)
hue- degree on the color wheel, saturation percentage value , 0% grey , 100% full color.

Background 
 
 Background-color-
 Background-image- url('');
 Background-repeat-no-repeat,repeat,x-repeat,
 Background-position - center
 Background-size, 100%(it fill Backgroundbut distort image),cover(make image big in size but it cut from side corner) , contain(Backgroundimage donot cut)
 Background-attachement- scroll,fixed
  


 Border

 border-style: double,dotted,dashed,solid,inset,outset
border-width: 



width,height
 Auto: it takes according to the content.
 %- percentage will be taken according to the parent body

 max-width: width would not greater than max-width,

 max-height:





 React

 To update a component with new data, two things need to happen:

Retain the data between renders.
Trigger React to render the component with new data (re-rendering).
The useState Hook provides those two things:

A state variable to retain the data between renders.
A state setter function to update the variable and trigger React to render the component again.


    import { useState } from 'react';
    const [index, setIndex] = useState(0);

    index is a state variable and setIndex is the setter function.


In React, useState, as well as any other function starting with “use”, is called a Hook.



destructuring in props:
destructuring is an es6 feature that allows us to unpacked the values from arrays or properties from object into
distinct variables. it increase code readbility. 

2 way 
1. destructuring in the parameter
2. destructuring in the function body
