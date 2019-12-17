# Instructions for uploading custom pyfirmata firmware onto JUAMI potentiostat
============================================================================

This is only required if you are building a potentiostat from scratch or if the
firmware was erased from your potentiostat.

1. Download the latest firmware from [https://github.com/juami/potentiostat_firmata](https://github.com/juami/potentiostat_firmata).
   This can be done from a Git prompt or directly from the URL.

2. Download and install the Arduino IDE at [https://www.arduino.cc/en/main/software](https://www.arduino.cc/en/main/software).

3. In the Arduino IDE, open pytentiostat_firmata.ino and plug the potentiostat into
   a USB.

4. Verify the Arduino Uno was found at Tools -> Port: "COMX (Arduino Uno)". Disconnect
   any other Arduinos to prevent any mistakes.

5. Press the upload button and verify that no errors occured. The words "Done uploading"
   will appear at the bottom with a green background. If the color turns red, there was
   an error.
