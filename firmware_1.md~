# Controller & firmware options

A, B, C are different options; choose the one you prefer – as always, at your own risk!

## A) Grbl on Ramps - default mpcnc (no dual end stops)
(and possibly others<sup>*1</sup>)
### Controller & firmware
&#42;1) *please report about any other boards in use including a link to documentation*

With the default mpcnc setup (non-dual end stop firmware & wiring) based on ramps, an approach is to use the [rgbl ramps](https://github.com/mschrock/grblForCyclone) solution by [@mschrock](https://www.v1engineering.com/members/mschrock/) et.al.

I followed the instructions there (downloaded the newest version from the *1.Download this repository* link pointing to the github of carlos. Compiled in arduino IDE ([as usual - see the section flash firmware](https://www.v1engineering.com/marlin-firmware/)) and flashed. I could not test it as I have the dual end-stop setup and don’t want to screw up my machine.
I have read of people using it successfully. *Perhaps someone could confirm this, then we could mark this here as confirmed.*

### Front-end

For boards running gbrl [bCnC](bcnc_1) is a great solution, as it runs on python and therefore should be available on many platforms.


## B) Grbl on Ramps – dual-end-stop, auto-squaring
### Controller & firmware

[@Pablo](https://www.v1engineering.com/members/enducross/) did great work [documented here](https://www.v1engineering.com/forum/topic/grbl-running-on-ramps/) to get it up and running, based on [grbl-Mega-5X](https://github.com/fra589/grbl-Mega-5X).

One or two end-stops per axis, NO or NC mode, all discussed in the linked thread!
See also the detailed tutorial [ZOOM on option B)](zoom_1.html).

The [‘main’ post](https://www.v1engineering.com/forum/topic/grbl-running-on-ramps/#post-78315) with the download link to the current version.

### Front-end
[bCnC](bcnc_1)

 
## C) General solution Marlin-mpcnc post in FreeCad

**Not yet** (I need to test it): provide an path: output: mpcnc-marlin option in FreeCad. Looks doable to me.
If you want to get this going, see and support [this](https://www.v1engineering.com/forum/topic/foss-marlin-pp-for-the-good-what-do-you-think/)

To be honest, I like this approach, as it would allow everybody to stick with the default firmware and his board.

There are some inputs on known issues and how these could be solved.<br>
[G0, G1, G17, g18/g19 & g2/g3 issue](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/#post-100222)<br>
[Jeffeb3's input](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/#post-100322)

**Any hint about possible other problems or approaches how to get some confidence (e.g. which commands to crosscheck) highly appreciated.**
<br>
*If someone whants to jump in - please contact me*

### Controller & firmware

Just the controller you have. Possibly two firmware parameters to adapt (ARC_SUPPORT and CNC_WORKSPACE_PLANES).

### Front-end

Just what you are using currently.


<br>
Feel free to dicuss your questions in the [related discussion thread](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/) 

