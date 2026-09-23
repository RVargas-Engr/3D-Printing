<p><img src=20260922_183044.jpg width=500></p>

## Overview
This holder provides a rigid wall attachment for the "Switchbot blind" product, which otherwise can have
a tendency to wrap itself around the mini blind wand if there is too much resistance in the wand mechanism.

It was designed in FreeCAD 1.1.1.

## Notes
To account for variations in mini blind models and installations, this 3D model is provided as a
FreeCAD parameterized design file.  Unfortunately, no single .STL or .3MF file will fit all setups.

To configure the object for your setup, load it in FreeCAD and find the "VarSet" item in the FreeCAD treeview.
In the VarSet, find the parameters called "this_switchbot_angle" and "this_wall_to_rod_center".  Change the
values of these parameters as described below to suit your installation.  There are other parameters in the
VarSet, but you can leave those values as they are.

"this_wall_to_rod_center" is a measure of the distance in millimeters from the wall to the center of the mini
blind wand.  It can be easily measured using a digital caliper or measuring tape.

"this_switchbot_angle" is a measure, in degrees, of the angle of the line that passes from the center of
the motor holder housing to the center of the wand with respect to the mini blind valance (assuming the mini
blind valance and wall plate are 90 degrees apart).  In my installations, this angle varied from 22 degrees to
45 degrees.  Most likely, you will have to make a best guess at the value for this parameter, print out the object,
and then make further parameter adjustments as needed.  Be sure to have the motor holder or wand restraint fully
inserted into its respective wall plate when making these kinds of measurements, as the parameter calculations
take into account the wall plate thickness.

Most likely, some or all of the Fillets will break after making a change in a parameter value, and this is
typical of a FreeCAD design.  If you want to preserve the filleted look, you will need to reassign the fillet
edges as needed after making parameter changes.

### How to mark the screw holes
The screw holes are necessarily placed above and below the motor holder stem, instead of to the left and right,
to minimize the possibility of there being a metal corner plate underneath the paint and joint compound.  As a
result, the Switchbot motor and the mini blind wand will get in the way when you want to mark the walls for
drilling.  To resolve this, the wall plates are designed as separate items that normally are friction-fit around
the motor holder stem and wand restraint.  Once you have the placement you want, simply detach the stem from the
wall plate and move it out of the way.  It may be helpful to disconnect the Switchbot motor from the blind as well.
