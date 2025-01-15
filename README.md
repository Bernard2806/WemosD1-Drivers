<div align="center">
  <img height="300" width="300" src="https://github.com/user-attachments/assets/183f0c6f-010a-4df5-86da-6007c684972d"  />
</div>

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
   ```
4. Click **OK** to save.
5. Go to **Tools > Board > Boards Manager**.
6. Search for "esp8266" and install the package.

### 3. Select Wemos D1 in Arduino IDE
1. Go to **Tools > Board > ESP8266 Boards**.
2. Select **Wemos D1 R1** or **Wemos D1 R2**, depending on your board.
3. Configure the correct COM port under **Tools > Port**.

### 4. Test Your Setup
1. Connect the Wemos D1 to your PC via USB.
2. Open **File > Examples > Basic > Blink**.
3. Upload the sketch and verify the LED blinks.

## Resources
- [ESP8266 Arduino Core](https://github.com/esp8266/Arduino)
