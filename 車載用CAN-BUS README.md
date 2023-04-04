# M5stack-OBD-CANgauge

OBD multi gauge for automobiles

CAN-BUS communication setting is 500kbps 
(1M will cause an error)

(1) Two types of data can be acquired and
 displayed by specifying IDs.
(2) Multiplication and offset are　
 possible.
(3) Indian is under confirmation.

CAN keypad　
Three switches send data 01 from
 ID 041A to byte 0 to 3.


Analog voltage value acquired by M5stack
 can be sent as CAN 8bit data from 
ID 3E8 byte0 to analog voltage 0 byte1 to
 voltage 1.


M5stack core and CAN-BUS unit for 
M5Stack (CA-IS3050G) are required.
