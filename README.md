# CNC_multipurpose_machine 
## Multipurpose CNC milling machine for wood and soft metal
## 
:exclamation:_Mark that this document is under work and that errors may
occur._
##
### Objective
This projects main objective is to build an inexpencive or expencive
extendable CNC milling machine for the hobbyist or for production use. The
machine can be built using simple or advanced materials depending on the users
need. There is no rule regarding type of materials or the type of software
used to control this machine. My choice will be a lightweight unit that can,
in some degree, be disassembled for transport or storage. It will also be
expandable from a normal 3 axis milling machine to a unit with all 6 axis plus
additional capabilities as described below.

### Hardware and capability
This machine will be primary for wood and plastic milling, but can in special
cases be used for soft metals like aluminium. Special care has to be taken in
theese cases, since there is no flood cooling, and thereby only dry milling
capabilities. There will be an air cooling/chip cleaning system with
pressurized air as medium.

### Axes and accuracy
This machine will have 6 active cnc-axes and some special alignment axes for
special operations. X, Y and Z is the standard Cartesian axes for spindle
movement, where X is left/right movement, Y is forward/backward movement and Z
is up/down movement. A, B are the Euler axises for table pitch and roll
respectively. These two axes can in normal operation only be rotated 180
degrees (+/- 90 degres). C is normally table yaw (rotation), but roll around
Z-axis is seldom used since this corresponds to the rotating axis of the tool
itself. If a rotation of the table is needed, this can be accomplished by
changing the table to a disc shaped table and reconfiguring the C axis to
rotate the table. This axis can now extend to a 360 degree rotation for
indexing etc. Normally, C is used as a special feed-through axis where long
materials or setups with multiple workpieces can be fed beyond the normal
Y-axis. This can also be used when a long milling operation has to be done in
the Y-axis without the need for special Y accuracy. Eg. edge-profiling. This
mode will in some cases require the material to have some unworkable endstock
in both ends to satisfy the feeding mechanism. It will also, in some cases
where high X accuracy is required, have to be equipped with special-made soft
jaws for the holding mechanism. It will also require special care regarding
the feed mechanism clamping capabilities. This axis can also be seen as the
legacy secondary Y-axis; The V-axis, as long as this axis is parallel to the
Y-axis. A and B axes are normally rotated to zero and not to be used when the
C axis is active, but the roll action (B-axis) can be implementet in the
feeding mechanism (not the table). This will be a >360 degree angle movement
along the length of the material (Y-axis), thus creating a lathe like
functionality with the milling tool (Z-axis) as the lathe X-axis (Tool in/out
axis). The A-axis could also be used as the tool angle axis (Lathe B-axis),
but that would require very special programming since this axis belongs to the
stock, not to the tool itself. Special alignment and reference marks has to be
created on the material to obtain some better accuracy in the Y-axis. More
Y-axis accuracy can also be obtained if special clamping tools are used.

### Sensors and adjustments
The machine will have optional sensors for sensing chatter, tool-load,
tool-bending and heat. It will also have sensors for stock height and edge
detection as well as different alignment sensors. These latter sensors will
also be used for sensing backlash, repeatability and axis accuracy.


### Construction
### 
### ### ### ### 
