> After upgrading, please manually restore the factory settings to ensure the device can continue to operate abnormally.

# Firmware Upgrade Method
## How to Upgrade on Windows
1. Extract WeActStudio_Upgrade_Tool.7z
2. Run WeActStudio_Upgrade_Tool.exe
3. Connect the device using a data cable
4. Select the fpk firmware
5. Open the serial port
6. Click the "Send" button to start the upgrade

## How to Upgrade on Linux, macOS or Windows
1. Extract WeActStudio_Upgrade_Tool_Python.zip
2. Connect the device using a data cable
3. Run WeActStudio_Upgrade_Tool.py, need to install pyserial library  
Example: python WeActStudio_Upgrade_Tool.py firmware.fpk
4. Wait for the upgrade to complete.

## How to Upgrade via Browser, Chromium-based Browsers Supported
1. Connect the device using a data cable
2. Open a browser and visit https://tools.weactstudio.com/FirmwareUpdater/
3. Follow the on-screen instructions

# Version History
**V1.0.2.0**
1. Add the timed output switch, which enables and disables the output according to the configured durations. An OFF Time of 0 runs the sequence once, a non-zero OFF Time repeats it in a loop.
2. Add five communication commands, covering over-current discharge, auto output, filter window, output compensation and timer settings.
3. Optimize the interface refresh rate.
4. Fix several issues.

**V1.0.1.0**
1. Add input voltage reading and PD input voltage read/write functions to the communication protocol.
2. Fix the WHO_AM_I command return value error in the communication protocol.

**V1.0.0.1**
1. Initial version
