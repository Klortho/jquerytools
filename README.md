Klortho fork of [jQuery Tools](http://flowplayer.org/tools/) - The Missing UI library for the Web
================================

This repo is forked form [Patrick64/jquerytools](https://github.com/Patrick64/jquerytools),
who forked from [jquerytools/jquerytools](https://github.com/jquerytools/jquerytools).
Patrick64 added support for touch devices to the rangeinput component.  I tweaked
that to make it work better on the Android browser, and also added two new API methods:

* setMax(max) - set a new maximum value, dynamically updating the handle position
* setRange(min, max, val) - change any combination of min, max, or value.  If any
  of these arguments is *undefined*, then that value will not be changed.
