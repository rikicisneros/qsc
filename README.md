# qsc

First release of QSC plugin automation for PAA20+ by Cinemanext Spain.

With this plugin all the 8 inputs and 12 outputs can be controlled and monitored from QSYS Designer:


![imagen](https://user-images.githubusercontent.com/45939598/226538058-b03d161f-b0b2-4d97-8bd2-b81e9683f402.png)

an output can be a change of state, or a pulse, all managed by TCP commands,  just with the IP and port (default is 10.0.0.180 and 10001 respectively)

Important update, in case other device is controlling the PAA20 device externally, Control mode must be settled to open and close the TCP connection on every poll request.

![imagen](https://user-images.githubusercontent.com/45939598/226538513-754abbbc-17a6-41a9-9e5f-972a13dabd40.png)
