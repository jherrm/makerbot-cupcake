Jeremy's Makerbot Cupcake Setup
===============================

Add the cupcake to ReplicatorG 39
---------------------------------

1. In OS X, right click ReplicatorG.app and select "Show Package Contents"
2. Add the contents of this repository's machines folder to ReplicatorG's `Content/Resources/machines` folder.

Configuring ReplicatorG 39
--------------------------

Select the correct machine driver:

    Machine -> Machine Type (Driver) -> Jeremy's Cupcake + MK5+Stepper Extruder
or

    Machine -> Machine Type (Driver) -> Jeremy's Cupcake + QU-BD Extruder

Select the legacy GCode generator:

    GCode -> GCode Generator -> Skeinforge (35) - Legacy

Generating GCode

    Slicing Profile: SF35-cupcake-HBP
    Use Raft/Support: FALSE
    Use support material: None
    Use default start/end gcode: TRUE
    Use Print-O-Matic (stepper extruders only): FALSE


Printing with ReplicatorG 39
----------------------------

Connect the cupcake USB cable to the computer and click connect in RepG.

Open the control panel and prepare the machine:

    Machine -> Control Panel

    Extruder temp: 220°C
    Build platform temp: 110°C


After the machine has warmed up, manually move the build platform/nozzle to X0, Y0, Z0 before starting the print due to the lack of endstops.
