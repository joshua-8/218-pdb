
16 3.3v

16 5v

24 plugs for 3.3v and/or 5v

4 plugs for 14v

two 5v buck converters (to isolate servos from other systems)

two 3.3v regulators (to isolate components and/or provide more current)

8 of the 3.3v and 8 of the 5v have signal wires brought out to separate pins so that for example all 3 wires of a servo could be plugged into the board and then the servo signal could be a socket-socket jumper wire from the pic board to the pdb (I think this could avoid cutting the plugs off of servos)

![render of board](/renders/top.png)
![render of board back](/renders/back.png)
![render of board perspective1](/renders/perspective1.png)
![render of board perspective2](/renders/perspective2.png)

## QUESTIONS / TODO:

* to disconnect the buck converters from the LDOs so that the buck converters can be set,  pull NT1

* final aligning of labels on silkscreen
* complete the BOM with all part numbers and values
    * make list of parts in readme by vendor
* add documentation to readme
* make documentation and diagrams
