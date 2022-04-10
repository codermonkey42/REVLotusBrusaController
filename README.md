# REVLotusBrusaZEVABridge
Code running on a **STM32 Nucleo-F303k8** board that reads battery status messages from a **ZEVA EVMS3** unit
And converts it into voltage, current parameters of a **Brusa NGL513** to control charge 
For the UWA REV Lotus car.

Additional features:
- 12V interrupt input to detect start of charger when charger ON and trigger comms to Brusa charger.
- LED control to indicate error status bit true.
