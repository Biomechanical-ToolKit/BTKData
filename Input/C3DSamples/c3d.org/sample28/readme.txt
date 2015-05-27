Two sample C3D files from a BTS system using TYPE-1 force plates.
One trial is dynamic, the other a static.

Although readable, these C3D files are missing several important
parameters such as POINT:DATA_START, POINT:SCALE, POINT:RATE etc
and contain duplicate POINT labels.

The third file "type1.c3d" has been created using the dynamic
data to represent a correctly formatted C3D file with TYPE-1
force plate data although the individual force plate scale
factors have not been verified.
