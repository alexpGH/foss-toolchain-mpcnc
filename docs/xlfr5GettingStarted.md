# XLFR5

## Installation

I build the main repo of André (the author of xflr5, aka *techwinder*).
In case of problems you can also try to build the [ubuntu specific patched version](https://github.com/polmes/xflr5-ubuntu).

```
svn checkout https://svn.code.sf.net/p/xflr5/code/trunk xflr5-code
```


Install prerequisites
```
apt-get install build-essential mesa-common-dev mesa-utils libgl1-mesa-dev libglu1-mesa-dev qt5-qmake libqt5opengl5-dev
```


Building
<br>Note: I initially had an error:
> cd xflr5-engine/ && ( test -e Makefile || /usr/lib/qt5/bin/qmake -o Makefile /home/alexp/wicht_soft/xflr5-code/xflr5/xflr5-engine/xflr5-engine.pro ) && make -f Makefile 
> Project ERROR: Unknown module(s) in QT: core gui
> make: *** [Makefile:49: sub-xflr5-engine-make_first] Error 3

Seems to have been fixed by installing libqt5opengl5-dev

```
cd xflr5-code/xflr5
qmake
make
sudo make install
sudo ldconfig
```
Finally, start xlfr5
```
xlfr5
```

<br>
## Export profile data from blender
Have a look at the block *'export 4 xlfr5'* in the helper file *planes/kissSlope/howtoAddMH30.py* discussed [here](../blenderAirfoils/#adding-a-new-2d-profile):

```
    coords=mh30modpk.coords('super',1.0,[0.0,0.0,0.0])
    filename=bpy.path.abspath("//MH30pk_xlfr5.dat")
    wingLib.foilExport(coords,'MH30pk',filename,'xlfr54spaces')
```
allows you to export the desired quality in XLFR5 format.



<br>
## Tutorial notes
I followed the [tutorial series](https://www.youtube.com/watch?v=U7saOcozpi8&list=PLtl5ylS6jdP6uOxzSJKPnUsvMbkmalfKg) of André (the developer of xlfr5 aka techwinder). The following notes are only meant as comments to the tutorials.

**Panel/points display (T1: 1:20)**
<br>right click the foil, 1st entry *current foil* > set style> set the style for points to points

**Refine loaded / new designed foil (T1: 1:30)**
<br>always: design>refine globally to 100-150 panels

**Design type1 for foils (T1: 3:55)**
<br>Type1 for foils, type 2 and 4 for planes





