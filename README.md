# AOG_IMU_ESP32
separate / external IMU for AgOpenGPS - supports CMPS14 + BNO080 / BNO085

An IMU gives you more accuracy at your GPS system. Changes in heading and roll can be correctd by AgOpenGPS immediately.

With This code you can place an ESP32 with a CMPS14 or BNO080/085 anywhere in your tractor. The messages will be send via USB or via WiFi or via Ethernet to you tablet.
For Ethernet you need an extra Ethernet shield for 3,3V. W5500 is recommended.

Connection: the IMU needs 3,3V, GND and I2C (SDA + SCL). The PINs can be set in the code.

Most settings can be done in the webinterface: connect you computer to the same Wifi network as the ESP32 and type the IP e.g. 192.168.1.75 (in access point mode 192.168.1.1) to your browser
