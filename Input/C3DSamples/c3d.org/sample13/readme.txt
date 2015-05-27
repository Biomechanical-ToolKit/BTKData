Sample data from a PhoeniX 3D system.

The first files recieved (DANCE.C3D and GOLFSWING.C3D) both contain errors:
    POINT:DATA_START is 0
    POINT:DESCRIPTIONS strings have a dimension length of 0.
    ANALOG:DESCRIPTIONS strings have a dimension length of 0.
    ANALOG:OFFSET is stored as a floating point value.
    FORCE_PLATFORMS:USED is missing.
  The first three errors listed above are critical and will prevent some
  C3D applications from reading the data correctly.

PhoeniX have since modified their C3D application to fix these problems
as shown in the two files DANCE1.C3D and GOLFSWING1.C3D which show be
readable by any C3D application.