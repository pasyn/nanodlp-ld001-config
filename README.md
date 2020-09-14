# Background
The Creality LD-001 is an entry level LCD resin printer. The original Chinese software that runs on the printer is extremely buggy and lacks customizability. Fortunately for us, this printer is powered by a Raspberry Pi 3 which makes replacing the software trivial. NanoDLP is a great candidate for this as it provides ready to flash images for the Pi 3.

# Prerequisites
- A new SD Card (16GB preffered) - Do not write over the original SD card. Put it aside in a safe place. Creality does not provided the original software for download should you want to go back.
- Balena Etcher - https://www.balena.io/etcher/
- The latest NanoDLP image for the Pi 3 - https://www.nanodlp.com/nanodlp.img.gz

# Installation
1. Using Etcher, flash your new SD card with the latest NanoDLP image.
2. Remove and reinsert the SD card. (Etcher unmounts the SD card after flashing)
3. Copy cmdline.txt and config.txt into the boot partition of the SD card.
4. Edit nanodlp-wifi.txt for your wifi network
5. Install the new SD card into the Pi on the printer
6. Turn it on and wait for it to boot
7. Open up the IP address of the printer in your web browser
8. Check for updates. Printer will restart after update.
9. Navigate to the tools menu and click on the expand filesystem button. The printer will reboot after the operation is completed.
10. Enter the following configuration into the machine settings menu.

```
WIP
```

