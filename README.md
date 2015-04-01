# CounterScroll

## What

* To create a dependable, configurable and logical method for manipulating the position of DOM elements relative to scroll position *without* the use of JS.
* Anything in addition to position control is a bonus.

## Why

It's easy to achieve scroll effects with JS but it usually comes at a high repaint/redraw cost when elements are being altered post render. There are ways to curb these effects but it would be preferable to eliminate JS in as many of these scenarios as possible.

## Known Things

* CSS is largely unaware of the scroll position of a document. Currently the only explicit reference to scroll I know of is the [`position: sticky`](https://developer.mozilla.org/en-US/docs/Web/CSS/position#Sticky_positioning) attribute.  It's still in [working draft](http://dev.w3.org/csswg/css-position-3/#position-property) but has potential for further control of these elements.


