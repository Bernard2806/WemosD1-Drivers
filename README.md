# Wemos D1 Windows Drivers

This repository provides the Windows drivers and setup instructions for the Wemos D1 board, including how to configure the Arduino IDE.

## Setup Instructions

### 1. Install the Windows Drivers
1. Download the driver from the [drivers/windows](drivers/windows) folder.
2. Extract the ZIP file and run the installer (`CH341SER.exe`).
3. Follow the on-screen instructions to complete the installation.

### 2. Configure Arduino IDE for Wemos D1
1. Open the **Arduino IDE**.
2. Go to **File > Preferences**.
3. In the "Additional Boards Manager URLs" field, add the following URL:
   ```plaintext
   https://arduino.esp8266.com/stable/package_esp8266com_index.json
