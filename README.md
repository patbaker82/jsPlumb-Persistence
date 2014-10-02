jsPlumb-Persistence
===================


Introduction
--------------

This plugin provides the ability to convert a jsPlumb diagram into a Json &amp; vice-versa.
Hence, providing the ever missing feature of persistence in jsPlumb.


`This plugin adds the following methods, to the jsPlumb global variable :`


`save(plumbInstance)`             //Returns a Javascript Object

`load(plumbInstace, savedObj)`


The plugin saves the graph connection details, anchors, overlays & style.


How To Use
-------------

`var savedObj=jsPlumb.save();`

`jsPlumb.load(savedObj);`
  



**Note**:Please make sure you to this plugin, after jsPlumb is loaded.
