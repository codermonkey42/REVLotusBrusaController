# REVLotusBrusaController
Code running on a **[STM32 Nucleo-F303k8](https://os.mbed.com/platforms/ST-Nucleo-F303K8/#technical-references)** board that reads battery status messages from a **ZEVA EVMS3** unit
And converts it into voltage, current parameters of a **Brusa NGL513** to control charge 
For the UWA REV Lotus car.

Additional features:
- 12V interrupt input (stepped down to 3V) to detect start of charger when charger ON and trigger comms to Brusa charger.
- LED control to indicate error status bit true.
