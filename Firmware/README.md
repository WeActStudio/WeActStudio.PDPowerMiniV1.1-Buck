> After upgrading, please manually restore the factory settings to ensure the device can continue to operate abnormally.

## Version History
**V1.0.1.0**
1. Add input voltage reading and PD input voltage read/write functions to the communication protocol.
2. Fix the WHO_AM_I command return value error in the communication protocol.

**V1.0.0.1**
1. Initial version

## How to Upgrade, Windows
1. Extract WeActStudio_Upgrade_Tool.7z
2. Run WeActStudio_Upgrade_Tool.exe
3. Connect the device using a data cable
4. Select the fpk firmware
5. Open the serial port
6. Click the "Send" button to start the upgrade

## How to Upgrade, Linux , macOS or Windows
1. Extract WeActStudio_Upgrade_Tool_Python.zip
2. Connect the device using a data cable
3. Run WeActStudio_Upgrade_Tool.py, need to install pyserial library  
Example: python WeActStudio_Upgrade_Tool.py firmware.fpk
4. Wait for the upgrade to complete.