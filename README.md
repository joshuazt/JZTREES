# JZTREES
Houdini procedural vegetation generator and FX toolkit

![JZTREESLOGO_256](https://user-images.githubusercontent.com/23189306/125146790-1aa98680-e16b-11eb-91e7-02d2d0a94058.png)

JZTREES is a set of tools for SideFX Houdini designed to ease the workflow for generating and applying FX to trees and vegetation.

## MINIMUM REQUIREMENTS

License Types: 

Apprentice or Indie. (no FX at this time).

JZTREES requires Houdini 18.5. Any version before 18.5 will not support procedural wind.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=4ZE72ALUPQV2E&no_recurring=0&currency_code=AUD)

##  INSTALLATION

Downloading JZTREES
1) Using gitclone download this repository to chosen location on your harddrive or shared network.

2) Download the zip from the repository then unzip the contents of JZTREES onto a chosen location on your hardrive or shared network. E.g. C://

NOTE: It is not reccomended to put JZTREES in your home houdini folder.

Installing JZTrees - VIDEO INSTALL: https://www.youtube.com/watch?v=aPHrA2YlDMw

In the JZTREES root there is a .json file which is used to point houdini towards where the toolkit is located.

1) Open the .json file in a text editor and adjust the variable "JZTREES" to match the location you have placed the toolkit.

E.g._ "JZTREES": "C:\Users\joshu\Documents\houdini_plugins\JZTREES",_

2) Open you houdini home folder. E.g. /houdini18.5. Following create a 'packages' folder in this location.

_If you already have a packages folder skip this step._

3) copy the .json file into the 'packages' folder.

4) To test the toolkit has installed correctly open houdini, go into a GEO node and try creating a JZTREE SOP. E.g JZT_Trunkgen

5) Success! enjoy using JZTrees


## NODE LIST

## GENERATORS

Modelling tools to generate trees and vegetation

JZT-TrunkGen - Generates Trunks

JzT-BranchGen - Generates Branches / fonds

JZT-LeafGen - Generates leaves

JZT-LeafInstancer - Instances geometry on to the tree

JZT-DetailGash - Tree Detail Generation for knots / gashes

JZT-CutterGen - Generates Cutter Geometry to input into the fracturing modifier


## MODIFIERS

JZT-Skeleton - Converts the tree splines into a kinefx rig

JZT-Wind - Generates procedural wind on the kinefx skeleton

JZT-Growth - Animates the kinefx skeleton to grow

JZT_WireSkeleton - Prepares the kinefx Skeleton for a wire simulation

JZT_AnimTransfer - Transfers animation (e.g. Wire simulation) back onto the kinefx rig and computes transforms.

JZT-SKINNING - Applies skeleton animation to geometry and leaves.

JZT-FRACTURING - Fractures geometry and prepares constants for bullet simulation.

## PRESETS

JZT-Fern - Example file of a Fern

JZT-PalmTree - Example file of a Palmtree

JZT-GumTree - example file of a Birchtree

JZT-ChristmasTree - example file of a Pinetree

JZT-WIRESIM - example file of how to setup a wire simulation with the skeleton. (Part of the GumTree)

JZT-BULLETSIM - example file of how to setup a deforming bulled simulation. (Part of the GumTree)





