# Foreword

Note: I use the blender interface for freecad (as I’m using blender regularly). Just right-click in the main window and select navigation-style> blender (shown in the 2nd video).

Note: After my initial tests with FreeCad, I opted for [blender](https://www.blender.org/) and the great [blendercam](https://github.com/vilemduha/blendercam) for design and gCode generation for complex parts (like airfoils). See my [motivation](blenderMot).

| Functionality | Shortcut      |
| :------------- |:-------------|
| 3D rotation   |middle mouse botton + move the mouse |
| Move the view |shift + middel mouse button + move the mouse |
| Scale         |mouse wheel or ctrl + middle mouse button + move the mouse |


# 0. Getting Freecad

Freecad provides appImages / binaries for Win / Mac / Linux. Just download and execute it. We will base this tutorial on the current stable release 0.18

[![Video – 0](http://img.youtube.com/vi/aXOwi4yDWuY/0.jpg)](https://www.youtube.com/watch?v=aXOwi4yDWuY)


# 1. Getting started: prepare for body creation
We will open part design and create a sketch (which is a 2D drawing, allowing for constraints etc.) which will then be the basis for the 3D body

[![Video -1](http://img.youtube.com/vi/uvMJVKm25mM/0.jpg)](https://www.youtube.com/watch?v=uvMJVKm25mM)


# 2.  Sketching a square, using constraints, extrude to body

[![Video -2](http://img.youtube.com/vi/NsnNnIFMbkQ/0.jpg)](https://www.youtube.com/watch?v=NsnNnIFMbkQ)


# 3. Adapting the geometry

How to use the underlying sketch (the constraints therein) to adapt the body geometry. This illustrates a basic design feature I like in freecad: all the steps build on oneanother (its like filters / adaptors applied in sequence). You can adapt almost all of them later on an the result will be adapted.

[![Video -3](http://img.youtube.com/vi/oMFNh4hp3A8/0.jpg)](https://www.youtube.com/watch?v=oMFNh4hp3A8)


# 4. Making a pocket

You can easily match a sketch on a face of a 3d body, do some 2d design and use it as the basis of 3D body modification.

[![Video – 4](http://img.youtube.com/vi/FBp4xR3D_J4/0.jpg)](https://www.youtube.com/watch?v=FBp4xR3D_J4)

# 5. Adding an island

[![Video – 5](http://img.youtube.com/vi/SoJ363wfyG8/0.jpg)](https://www.youtube.com/watch?v=SoJ363wfyG8)

# 6. Configure the path workbench, create the pocketing operation

[![Video -6](http://img.youtube.com/vi/1RDEcL7GOIQ/0.jpg)](https://www.youtube.com/watch?v=1RDEcL7GOIQ)

# 7. Visualize and correct the finishing allowance
In the last video we generated the pocketing operation; checking the visualization we recognize that we had used the wrong sign for the finish allowance and correct it here

[![Video – 7](http://img.youtube.com/vi/3qmyA0SOTy8/0.jpg)](https://www.youtube.com/watch?v=3qmyA0SOTy8)

# 8. Export gcode

[![Video – 8](http://img.youtube.com/vi/Hlzd1YXwUFM/0.jpg)](https://www.youtube.com/watch?v=Hlzd1YXwUFM)
 
# Open points
+ check if we could have holding tabs generated: thanks to @edwardvmills: holding tabs are called ‘tags’ and are available as a ‘Dressup’ on an operation. tutorial tbd.
+ we use 5mm in z. add a short video to show how to use a plunge angle and smaller milling depth per pass
+ 3d milling

<br>
Feel free to dicuss your questions in the [related discussion thread](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/) 

