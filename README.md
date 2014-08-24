## About floatLabels:

A jQuery (and Zepto) form "float label" plugin.

The javascript adds a class to containers of inputs which have content in them.

If no label is found one will be created from the input placeholder or name. If no id is found one will be generated.

[floatLabels.css](https://github.com/cwmonkey/floatLabels/blob/master/floatLabels.css) is not required, but some sort of styling will be needed for the float label effect.

[example1.html](https://github.com/cwmonkey/floatLabels/blob/master/demo/example1.html) has some minimal css which relies on the js to add the js-float-labels-wrapper class.

[example2.html](https://github.com/cwmonkey/floatLabels/blob/master/demo/example2.html) has css which doesn't rely in js classes, but rather classes provided by the initial html.

See [floatLabels.js](https://github.com/cwmonkey/floatLabels/blob/master/floatLabels.js) for more information/parameters.

Note: if the input's value is updated with javascript, a change event must be triggered (.change())

## Changelog:

### Version 1.0 - August 23 2014
* First release
