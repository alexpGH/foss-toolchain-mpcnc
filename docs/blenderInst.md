# Installation

##Blender##
I currently use [blender](https://www.blender.org/download/)'s long term support version 2.83.9 (on linux) spcifically the tgz download, unpack and therein start blender. This allows me to use different versions in parallel (just in case).

**Add-ons**
<br>For the curve simplification check to have edit>preferences>add-ons> Add curve: simplfy curves+ activated

**Python modules**
<br>Blender comes with a bundled python in whereYouUnpacked/blender-2.91.0-linux64/2.91/python/bin

First check to have an up to date pip3 in the bin dir:

```
cd whereYouUnpacked/blender-2.91.0-linux64/2.91/python/bin
./python3.7m -m ensurepip
./python3.7m -m pip install -U pip
```
Now you can install python modules
```
./pip3 install matplotlib
```
For the foil analysis stuff, we need to be able to read / write xml files and tehrefore need

```
./pip3 install beautifulsoup4
```



##BlenderCam##

In order to be able to use [blendercam](https://github.com/vilemduha/blendercam) follow the [documentation](https://github.com/vilemduha/blendercam/wiki).
I might later on add some notes here, but for now concentrate on the scripting part for wing design.

