Semi-Fluid Layouts for Bootstrap

Installation
------------

Include `semi-fluid.css` in your project.

Available classes
-----------------

`semi-fluid-container`


Usage
-----

All fixed and fluid row classes must be used within an element with the `semi-fluid-container` class. The container defult to `fluid` (width: 100%) but can be changed `fixed` (width based on xs, sm, md, lg default breakpoints) by adding the `fixed` class to the container (which will effect all rows within that container). Individual rows behavior can be changed by adding `fixed` or `sm`/`md`/`lg` `-fixed` to the row (or `fluid` or `sm`/`md`/`lg` `-fluid` if the containers default behavior has been changed to fixed) to apply to all viewport widths equal or above the specified breakpoint size. `lt-` can be prefixed to the above classes to apply fixed/fluid if the viewport is **l**ess **t**han the specified break point.

Future Updates
--------------

A SASS version will be added later.