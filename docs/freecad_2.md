# Install opencamlib

Note: After my initial tests with FreeCad, I opted for [blender](https://www.blender.org/) and the great [blendercam](https://github.com/vilemduha/blendercam) for design and gCode generation for complex parts (like airfoils). See my [motivation](blenderMot).

Get it [here](https://github.com/aewallin/opencamlib) and build it. Simple cmake build.
<br>On my linux system, after installation even after checking that everything is installen in */usr/local/lib* and executing `ldconfig /usr/local/lib` for Freecad to find in () I got

    OpenCamLib is not working!

when starting Freecad and the path workbench.

The second option is to copy the compiled librarie(s) in the macro folder.
Find out the macro path in freecad preferences.

![](./assets/images/xfree1.png " ")

and copy

<br>
Feel free to dicuss your questions in the [related discussion thread](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/) 

