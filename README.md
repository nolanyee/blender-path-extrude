# Path Extrusion Tool for Blender
### Overview
To use this tool, select one polygon curve and another polygon path. The selected curve is extruded along the polygon path. This is achieved by extruding the loop towards each point on the path. The pivot of the curve is translated to the points on the path. The orientation is such that the normal vector of the best-fit plane of the curve is parallel to the path at all points on the path except the first point, for which the original orientation of the curve is used. When the path takes sharp turns, mitering is accomplished by scaling the loop in a manner dependent on the angle of the path.

<img src ="images/ExtrudePath1.jpg" width = "900">

### Technical Details
The curve (the first polygon to be selected) consists of connected points. The points and pivots are named as shown below, as an example.

<img src ="images/ExtrudePath2.jpg" width = "500" align="left">

The path also consists of connected points, named below as an example.

<img src ="images/ExtrudePath3.jpg" width = "400" align="left">
