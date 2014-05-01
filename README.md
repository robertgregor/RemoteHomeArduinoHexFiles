RemoteHomeArduinoHexFiles
=========================

RemoteHome Hex files for arduino devices. The copy of this repository is on www.remote-home.org/hexfiles/

The structure of the versions.txt file:

Example:

sketch_simpleSwitch.cpp.hex 1
sketch_TemperatureMeter.cpp.hex 1
sketch_transceiver.cpp.hex 2


Format of each line:

HexFileName Version\n


Meaning:

HexFileName - the name of the hex file. Should exactly match with the file name.
Version - Version of the firmware. If the stored version is lower than this number, the software should offer to get the new version.