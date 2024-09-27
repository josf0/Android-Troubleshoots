# Android-Troubleshoots
Troubleshoot and tips for android, adb and other related things

# ADB
1. Device not detected under fastboot
Sol.  1. Download the fastboot drivers from this link [Fastboot Drivers](https://drive.google.com/drive/folders/1TW2JjkujvgabfV-yXSzw3jLXk6xg_wkK?usp=sharing)
      2. Open up windows device manager.
      3. There should be a device with yellow warning, right click and select update driver.
      4. Select let choose from device and point to the fastboot directory saved and that should update the driver showing the bootloader driver has been installed.
      5. Open up adb and enter `fastboot devices` and check if the device has appeared.
      
