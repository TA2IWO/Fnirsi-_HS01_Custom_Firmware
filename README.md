# 🔧 FNIRSI HS-01 Custom Firmware

An open-source, browser-based firmware customization tool for the **FNIRSI HS-01 soldering iron**, featuring personalized startup logos and **LiPo battery low-voltage cutoff protection**.

> ⚠️ **Compatibility:** This tool supports **only the original FNIRSI HS-01 V0.3 firmware**. Other firmware versions are not supported and may cause errors.

## 🚀 Installation & Usage

### 1. Download the Official Firmware

Visit the [FNIRSI Official Firmware Download Page](https://www.fnirsi.com/pages/manuals-firmwares).

Download the following files for the **HS-01**:

- Original V0.3 firmware (`.s19`)
- Official Firmware Update Tool

### 2. Download the Customization Tool

Download `index_V2.html` from this GitHub repository.

Open the file using your preferred web browser. No installation is required.

### 3. Load the Original Firmware

Upload the original **V0.3 firmware** into the web interface.

**Important:** Only V0.3 is supported. Other firmware versions will result in an error.

### 4. Customize Your Firmware 🎨

Personalize your soldering iron with the available customization options:

- **Custom Text:** Display your own text during startup.
- **Custom Logo:** Upload a JPEG image as your startup logo.
- **Original Logo:** Keep the factory startup logo unchanged.
- **LiPo Protection:** Configure the available low-voltage cutoff settings.

### 5. Generate the Patched Firmware

Once you've finished customizing:

1. Click the firmware generation button.
2. Download the generated patched `.s19` firmware file.
3. Save it somewhere accessible on your computer.

### 6. Enter Bootloader Mode

1. Disconnect the soldering iron from your computer.
2. Press and hold the **left arrow button (◀)**.
3. While holding the button, reconnect the soldering iron using a USB data cable.
4. The display should show **Bootloader**.

Your device is now ready for firmware flashing.

### 7. Flash the Custom Firmware

1. Open the official **FNIRSI Firmware Update Tool**.
2. Select the appropriate device/COM port.
3. Load your newly generated patched `.s19` file.
4. Start the firmware update.
5. Wait until the update is completed successfully.

**⚠️ Do not disconnect the USB cable during the firmware update.**

### 8. Enjoy Your Custom Firmware! 🎉

Restart your FNIRSI HS-01 and enjoy your personalized startup screen and additional functionality!

---

## ↩️ Restore the Original Firmware

Want to return to the original FNIRSI firmware?

You can restore the factory firmware at any time, provided the device can still access its bootloader.

1. Download the original **HS-01 V0.3 firmware**.
2. Enter **Bootloader Mode**.
3. Open the official FNIRSI Firmware Update Tool.
4. Flash the original firmware file.

Your soldering iron will return to the manufacturer's original firmware functionality.

## ⚠️ Important Notes & Disclaimer

- **Original firmware is not included.** To respect the manufacturer's intellectual property rights, this project does not distribute original firmware files, proprietary code, or internal firmware details.
- Users must obtain their own legitimate copy of the original V0.3 firmware.
- This project is independently developed and is **not affiliated with or endorsed by FNIRSI**.
- Firmware modifications are performed at your own risk. Incorrect flashing may cause device malfunction.
- LiPo low-voltage cutoff is an additional safety feature and does not replace a dedicated battery management or protection circuit.

---

## ❤️ Support the Project

If you find this project useful, consider giving the repository a ⭐ **star on GitHub**!

Your support helps motivate further development and improvements.

**73 de TA2IWO**
