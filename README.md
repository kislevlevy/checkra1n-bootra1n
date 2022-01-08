How to Jailbreak A7 Devices using checkra1n on bootable USB drive
===========================

## Step 1 You will need:
- USB flash drive (You also can burn a DVD).
- USB 2 lightning cable.
- 64-bit or 32-bit AMD or Intel PC.
- A7 chip up to date device - [Link](https://en.wikipedia.org/wiki/Apple_A7#Products_that_include_the_Apple_A7).

## Step 2 - Download bootra1n:
- You can seek the latest version here - [Link](https://pangu8.com/jailbreak/bootra1n/).

## Step 3 - Write bootra1n to USB:
- Using Rufus - [Link](https://rufus.ie/).
- Download Rufus. (I recommend the portable version)
- Press SELECT, open the "bootra1n" ISO file, and press START to flash it to your USB drive.
> It will erase your drive!

## Step 4 - Reboot and run checkra1n:
- Select the flash drive on boot device options on your PC.
- Choose USB SAFE MODE!
- And it should boot into the login prompt
- Log in as `anon`, with password `voidlinux`.
- At the $ prompt, enter- `sudo checkra1n`.

## Step 5 - Jailbreak:
- Plug your device into your PC. Trust your device if necessary.
> Remove touch id and passcode before entering the setup.
- The checkra1n app should automatically detect your device and firmware type.
- Click the Start button (using your arrow and enter keys to navigate).
- Checkra1n will want to put your device into Recovery Mode before proceeding. Click the Next button.
- You will now want to follow the on-screen instructions to enter DFU mode.
- After you successfully enter DFU mode, checkra1n will begin exploiting and jailbreaking your device.
- After 2-5 minutes in "this is the real bug setup" you will get the following error message: `INFO: task checkra1n:1100 blocked for more than 122 seconeds.`
- Disconnect your device till you get this message: `DFUSyncUpload FAILED: -1`.
- Than reconnect your device. (quickly)
- Now the Operation should continue as normal and youll see `booting...`.
- Your iOS device should now display the checkra1n-themed verbose boot screen.
>Do not disconnect it until after the jailbreak completes.
- After the jailbreak finishes, you can click on Done and disconnect your device.

## Step 6 - Installing Cydia:
- On your iOS device, you should now see the checkra1n loader app on the Home screen.
> It may take up to 5 minutes to appear (If not repeat setup from start).
- Open it, tap on the Cydia app, and Install Cydia.
- The checkra1n loader will then begin downloading the base system and installing Cydia.
> It may reboot your device.
- When finished, the app will close and Cydia will appear on your Home screen.
Congratulations, jailbreak complete!

## Credits
- Bootra1n repository - [Link](https://github.com/foxlet/bootra1n)
- Checkra1n - [link](https://checkra.in/)
- Checkra1n community on reddit - [Link](https://www.reddit.com/r/checkra1n/)
- Pangu8 -  [Link](https://pangu8.com/)
- Rufus - [Link](https://rufus.ie/)
- Void OS - [Link](https://voidlinux.org/)

### My Reddit post - [Link](https://www.reddit.com/r/checkra1n/comments/ryx57v/how_to_jailbreak_a7_devices_using_checkra1n/)
### My YouTube Guide - [Link](https://youtu.be/VDDRCB7Waqg)
