# Path Extrusion Tool for Blender
## Description
This tool allows you to select one polygon loop and another polygon path. The selected loop is extruded along the polygon path. This is achieved by extruding the loop towards each point on the path. The orientation is such that the normal vector of the best-fit plane of the loop is parallel to the path at all points on the path except the first point, for which the original orientation of the loop is used. When the path takes sharp turns, mitering is accomplished by scaling the loop in a manner dependent on the angle of the path.
