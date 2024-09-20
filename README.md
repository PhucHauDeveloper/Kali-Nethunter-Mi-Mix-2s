# Kali-Nethunter-Mi-Mix-2s
## This is a synthetic version as well as a test of installing Nethunter on Mi Mix 2s device, it is not officially supported.
Here's your guide translated and rephrased in a more professional and clear manner:

---

**Guide to Flashing a Custom Kernel for Kali NetHunter on Xiaomi Mi Mix 2S**

Before you start, I recommend using MIUI 12.5 or any AOSP-based ROM running Android 11. While I have successfully tested some Android 12, 13, and even 14 versions, there may be issues such as Bluetooth not working or, in the worst case, the device failing to boot. To prevent potential damage, you should back up your boot partition beforehand.

Once you accept the possible risks to your data and are using the correct version, follow these steps:

1. **Root your device:** Ensure that your device is rooted.
2. **Enter custom recovery:** Boot into a custom recovery (TWRP, OrangeFox, or any third-party recovery that supports Sideload).
3. **Flash Magisk:** First, flash Magisk, then reboot back into recovery.
4. **Flash the custom kernel:** After rebooting into recovery, proceed to flash the custom kernel.
5. **Boot into the system:** Once flashing is done, reboot into the system and wait for the process to complete.

**Note:**
If you’re using your device as a dedicated network testing tool and don't need Android, and your screen is still original (not replaced), I can show you how to run NetHunter Pro.

To get started, download the necessary files and follow these steps:

Boot your device into fastboot mode.

Run the following commands:
  ```
fastboot flash userdata nethunterpro-20240822-sdm845-phosh.rootfs.img
fastboot flash boot nethunterpro-20240822-sdm845-phosh.boot-polaris.img
fastboot erase dtbo
  ```
After flashing, reboot the device. The default password is 1234.

I will provide additional instructions for dual booting with Android, Windows, and other configurations once I get an original screen for my device.

Let me know if you need further details or clarifications!

Good luck!
