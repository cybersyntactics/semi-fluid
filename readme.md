Semi-Fluid Layouts for Bootstrap
================================

Installation
------------

Include `semi-fluid.css` in your project.

Available classes
-----------------

`semi-fluid-container`

 * `sm`/`md`/`lg` `-fixed`

 * `sm`/`md`/`lg` `-fluid`

 * `lt-` `sm`/`md`/`lg` `-fixed`

 * `lt-` `sm`/`md`/`lg` `-fluid`



Usage
-----

All fixed and fluid row classes must be used on a row (or nested row) within an element with the `semi-fluid-container` class. The container defults to `fluid` (width: 100%) but can be changed to `fixed` (width based on sm, md, lg default breakpoints) by adding the `fixed` class to the `semi-fluid-container` element (which will effect all rows within that container). Individual rows behavior can be changed by adding `fixed` (or `fluid` if the `semi-fluid-container` class element also has the `fixed` class) to that row (affecting all sizes) or `sm`/`md`/`lg` `-fixed` to the row (or `sm`/`md`/`lg` `-fluid`) to apply to all viewport widths equal to or above the specified breakpoint size. `lt-` can be prefixed to the above classes to apply fixed/fluid if the viewport is less than the specified break point.

Future Updates
--------------

A SASS version will be added later.