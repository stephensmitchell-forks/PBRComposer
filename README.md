# PBRComposer
## overview
In short, PBR Composer helps you design and visualize a PBR Material in an efficient way. Parameterizing takes place by dragging and connecting specific nodes from a palette (typically textures, colors and uv-coordinates) to the output node, which represents the PBR Material. A preview panel lets you see all changes in realtime and the corresponding js-sourcecode will be updated as well. The resulting graph  can be downloaded in JSON format for later use. Images can be inserted via preview fileselect dialog and/or Drag&Drop, in latter case the images will be transformed to embedded data-urls so the javascript functions can be reused without dependencies. Different meshes and environment-maps are available to see the material under different geometry and reflective light conditions.
## motivation
Due to the complexity of the PBR material (soo many combinations with soo much amazing effects) there is a need of having realtime feedback reflecting the changing parameters. Other than some editor already out using a bunch of parameters in confusing properties panels, nodes lets you to concentrate only on the parameters you need giving a nice overview in form of a graph. Nodes can also be shared and avoids therfore redundancy in the sourcecode. The goal is/was to make the user interface as efficient as possible. The idea for realizing the PBR Composer was inspired from **Shader Editor** (http://victhorlopez.github.io/editor/).
## technical details
PBR Composer is a web application based on **dat.gui** (https://code.google.com/p/dat-gui/), **w2ui**(http://w2ui.com/web/), **litegraph.js** (https://github.com/jagenjo/litegraph.js), **Litegl.js** (https://github.com/jagenjo/litegl.js), **Font-awesome** (http://fortawesome.github.io/Font-Awesome/) and of course on **BABYLON.js** (https://www.babylonjs.com/). 
## installation
All dependencies and the PBRComposer itself is bundled inbetween the src directory. For installation the only task to do is to copy the content of the source directory of your web space. Point the browser to this place and you are ready to go.
