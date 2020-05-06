# Battery-Management-System
Battery Management system implementation with integrated RTOS and MODBUS facility.(For Arduino and Similar Micro controllers.


BMS Manual.txt
Last month
Apr 6

You changed permissions on an item
Text
BMS Manual.txt

Can view
M2MLogger Embedded Dev Team
Can view
Anyone with the link
Last year
Jul 1, 2019

You uploaded an item
Text
BMS Manual.txt
PLEASE NOTE THAT :

The operating range for Battery Voltage Sensing :  0-25 V(Safe Operation)
The operating range for Panel Voltage Sensing   :  0-25 V(Safe Operation)
The operating range for Battery Current Sensing :  0-5A
The operating range for Panel Current Sensing   :  0-5A
Error is readings                               :   ±1% of Multimeter readings having a maximum error rating of .1%
Wattage of the BMS : <=0.8W 

Features:

Voltage Monitoring. 
Current Monitoring.
Power/Load Monitoring.
Energy Monitoring.
Charge / Discharge Monitoring.
Communication over RS485.




USER GUIDE:


--The recommended software for Modbus Communication with the device is MODSCAN (either32 bit or 64 bit according to the software installed)
                 The holding registers have been used and the baud rate of the device (BMS) is set to 9600 bits per second.


The address of the holding registers (4XXXX) used in MODBUS COMMUNICATION

---Battery Voltage at 40001
---Battery Current at 40002
---Battery Power at   40003
---Battery Energy at  40004
---Panel Voltage at   40005
---Panel Current at   40006
---Panel Power at     40007
---Panel Instantaneous Energy (i.e. - Per second ) at 40008


WORD LENGTH = 8
Parity = NONE
BAUD RATE = 9600
STOP BITS = 1
