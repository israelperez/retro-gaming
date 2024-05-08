# Anbernic Stock OS Theme install

A Theme usually contains all its assets in a folder, an installation .sh script and a thumbnail img.

## Installation

1. Extract the zip file and it should spit out a folder called APPS that contains everything the theme uses.
2. The APPS folder also exists on the sd card in your ROMS folder. So just copy the contents there.
3. Then place the SD card back into your device and boot it up.
4. Navigate to RA EMULATION > APPS and the theme install script should be there now. Just run it and it will reboot with the new theme installed.

## Change the boot screen

There are 2 boot images used by the Anbernic OS. One is the OS boot image and the other is the theme boot image.

### how to change the theme boot image

The boot screen for the theme is located at

```
APPS/Theme-Synthwave/res1/boot/logo.png
```

1. Simply select the image you want to use, it doesn't have to one ive included just make sure it matches the pixel dimensions ie 640 x 480.
2. Rename the file to logo.png and replace the one default one in the theme.
3. Run the theme installation script again and it will set up the theme again with the new boot screen.
