# Path Extrusion Tool for Blender
### Overview
To use this tool, select one polygon curve and another polygon path. The selected curve is extruded along the polygon path. This is achieved by extruding the loop towards each point on the path. The pivot of the curve is translated to the points on the path. The orientation is such that the normal vector of the best-fit plane of the curve is parallel to the path at all points on the path except the first point, for which the original orientation of the curve is used. When the path takes sharp turns, mitering is accomplished by scaling the loop in a manner dependent on the angle of the path.

<img src ="images/ExtrudePath1.jpg" width = "800">
###
