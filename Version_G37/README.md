Software Implementation of PLC with STM32 "bluepill" hardware.

Version G37 -
For now you can use all 8000 steps in you program. This version not for field or industral use, and now you can use only 4 input and 4 output. Also you can use all posibility for master and slave modbus, but only 50 requests.
From this version modbus slave adress is fixed - 111 for UART1 and 112 for UART2.
Also you can program device from any port( not only USB VCP), connected as modbus slave.
