# Wi-Fi Driver: MediaTek MT7920 (Honor MagicBook AMD)

[🇷🇺 Читать на русском (Read in Russian)](README_RU.md)

This repository was created for users who are facing non-working Wi-Fi issues on Honor laptops (specifically AMD Ryzen models). The official driver provided by the manufacturer often fails to install or work correctly. 

Here is a working driver extracted directly from a system where it functions perfectly.

## Tested Device Specs
*   Laptop Model: HONOR GOH-X (SKU: C170)
*   Processor: AMD Ryzen 5 6600H
*   OS: Windows 11 (Build 26300.9711)
*   Wi-Fi Module: MediaTek Wi-Fi 6 MT7920 Wireless LAN Card

Hardware IDs
To ensure this driver is compatible with your device, check your Hardware ID in Device Manager. It should match one of the following:
*  PCI\VEN_14C3&DEV_7920&SUBSYS_E141105B&REV_00
*  PCI\VEN_14C3&DEV_7920&SUBSYS_E141105B
*  PCI\VEN_14C3&DEV_7920&CC_028000
*  PCI\VEN_14C3&DEV_7920&CC_0280


Driver Version
*   Version: 3.4.0.1281
*   Date: 09.06.2025

Installation Guide
Since this is an extracted driver (not an `.exe` file), you need to install it manually via Device Manager:

1. Download the driver folder from this repository (click `Code` -> `Download ZIP`).
2. Extract the ZIP archive to any convenient folder.
3. Press `Win + X` and open Device Manager.
4. Locate your Wi-Fi adapter (it might be named "Unknown device" or "MediaTek..." with a yellow warning sign).
5. Right-click on it and select Update driver.
6. Choose Browse my computer for drivers.
7. Click Browse and select the path to the folder where you extracted the driver.
8. Click Next and wait for the installation to finish.

---
*⚠️ Disclaimer: The driver is provided "as is". You install it at your own risk. The repository author is not the developer of this software.*
