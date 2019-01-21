# DrawingInVr

Set of export insttructions to use VR models from Blocks, Tiltbrush and Gravity Sketch

## Dependency

+ DO NOT UPDATE STEAMVR PLUGIN! Project uses [SteamVR v1.2.3 plugin](https://www.youtube.com/watch?v=gvcifdn_9qI) NOT the current SteamVR version. Otherwise VR prefabs will be blank and Tiltbrush stuff will be broken.


## Blocks/Poly

+ [Check Poly toolkit for Unity on github for updates and info on importing workflow](https://github.com/googlevr/poly-toolkit-unity)
+ [Check online documentation](https://developers.google.com/poly/develop/unity)
+ [Follow the workflow on Google Developers to set up Poly account for your Unity app](https://developers.google.com/poly/develop/unity)
+ Get an API key for your ID! Make sure unity project name and API key match.
+ To access private assets you will need to congifure a Google API Dashboard to use the Poly API. This sends your credentials to be able to download your assets. It will require a specific dashboard for your project e.g. DrawingInVr. Instructions for this are on the Google Developers Help page linked above.

### Import raw shape w/o colours

+ Open blocks, get into Vive
+ Draw something
+ Save it locally
+ Go to C:\ThisPC\Documents\Blocks\OfflineModels
+ Find your model folder
+ Import into project, this way does not preserve 

### Import w colours

+ Open blocks, get into Vive
+ Draw something
+ Save it online (requires signin), you don't have to publish it for it to be available to use in Unity.
+ Open Unity, open Poly Toolkit tab, Show: "Your uploads", maybe refresh (requires signin)
+ Select asset, Import into project.

## Tiltbrush

+ API already installed in Unity project to export Tiltbrush sketches directly into Unity
+ [Check Tilbrush API for Unity on github for updates and info on importing workflow](https://github.com/googlevr/tilt-brush-toolkit)
+ [Check online documentation](https://docs.google.com/document/d/1YID89te9oDjinCkJ9R65bLZ3PpJk1W4S1SM2Ccc6-9w/edit)

### Import sketch locally

+ [Follow instructions here](https://docs.google.com/document/d/1YID89te9oDjinCkJ9R65bLZ3PpJk1W4S1SM2Ccc6-9w/edit)

### Import sketch from online

+ Open tilbrush, get into Vive
+ Draw something
+ Save it online (requires signin), you don't have to publish it for it to be available to use in Unity.
+ Open Unity, open Poly Toolkit tab, Show: "Your uploads", maybe refresh (requires signin)
+ Select asset, Import into project.

## Gravity Sketch

+ There is a lot of specific controls for this app, check their [user intro presentation for info before starting](https://www.gravitysketch.com/learn/)
+ To export, use inbuilt menu and find the model in documents e.g. C:\ThisPC\Documents\Gravity Sketch\Exported Sketches, unzip it and [import into Unity like any other asset](https://docs.unity3d.com/Manual/HOWTO-importObject.html)