# GPS Logger

Building on PlatformIO with Adafruit GPS has [issues](https://community.platformio.org/t/adafruit-gps-library-cannot-compile-because-softwareserial-is-missing/18703/3), when creating this.

The workaround is to replicate the Adafruit_GPS library in the lib folder and remove the comments around SoftwareSerial.h include.