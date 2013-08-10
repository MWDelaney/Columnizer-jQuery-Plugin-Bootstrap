Columnizer-jQuery-Plugin-Bootstrap
==================================

A modified version of [Adam Wulf's jquery.columnizer](https://github.com/adamwulf/Columnizer-jQuery-Plugin) which applies Bootstrap 3 column classes for responsive design.

Major changes in this version over the original version:
* buildOnce defaults to "true"
* Instead of inline styles, columns now receive the following:
````
<div class='" + className + " col-lg-" + (Math.floor(12 / numCols))+ "'></div>
````