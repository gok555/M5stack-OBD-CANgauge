# M5stack-OBD-CANgauge&GPStoCAN

This is for the M5sack series, which is mainly used in connection with vehicle CAN-BUS systems.
All files are created in UiFlow (blockly).


In the ZIP file are four types
(1) to (3) OBD gauges are wireless type communicating by ESPNOW.

1(GitFromCoreOBDmoniRXcore2.m5f)

M5 core only for OBD gauge monitor

2(GitOBDgaugeTXcoreESPNOW.m5f)
GitOBDgaugeTXcoreESPNOW.m5f for OBD Gauge Vehicle Side Transmission Unit

3(GitOBDgaugeRXAtomTXcore2 ESP NOW.m5f)
For Atom only OBD Gauge Monitor

4(GPStoCANspeed2HzEspNow.m5f)
For AtomGPS Requires genuine CAN controller CANBUS UNIT (CA-IS3050G)
GPS chip speed needs to be changed to 2Hz in u-senter. If using default 1Hz, timer update speed needs to be adjusted in the program.


