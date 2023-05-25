# BlueRetro Universal HW1
A basic board meant to be used with the [BlueRetro project](https://github.com/darthcloud/BlueRetro) to simplify basic “HW1” internal installation in various supported consoles. Including onboard level shifting 3.3v regulation for consoles which don’t provide it.

### Bill of Materials
- [ESP-WROOM-32 Module](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32_datasheet_en.pdf)
- 2 x [TXS0108E 8-Bit Bi-directional, Level-Shifting, Voltage Translator](https://www.ti.com/lit/ds/symlink/txs0108e.pdf)
- 0805 1kΩ Pull-up Resistor for TXS0108E
- [AMS1117-3.3 3.3V 1A Low Dropout Voltage Regulator](http://www.advanced-monolithic.com/pdf/ds1117.pdf)
- 2 x 0805 Decoupling Capacitors for AMS1117 (I'm unsure of appropriate values, 1μF is what I used)
