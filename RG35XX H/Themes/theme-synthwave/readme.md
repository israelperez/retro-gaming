# Anbernic Stock OS Theme install

A Theme usually contains all its assets in a folder, an installation .sh script and a thumbnail img.

## 1. Installation

1. Extract the zip file and it should spit out a folder called APPS that contains everything the theme uses.
2. The APPS folder also exists on the sd card in your ROMS folder. So just copy the contents there.
3. Then place the SD card back into your device and boot it up.
4. The latest Stock OS Update or Stock mods have moved the APPS icon. If so navigate to APPS > APPS or navigate to RA EMULATION > APPS. One of these should work. Once you're in APPS, the theme install script should be there now. Just run it and it will reboot with the new theme installed.

## 2. Change the boot screen

There are 2 boot screens used by the Anbernic OS and when you turn your device on, they will appear in the following order:

1. OS boot screen (BMP)
2. Theme boot screen (PNG).

This theme uses the same image for both as default. On my personal device ive changed the OS boot screen to the device specific one that shows my devices model number and kept the default theme boot screen.

### 2.1. How to change the OS boot image

The boot screen for the theme is located at

```
APPS/Theme-Synthwave/boot/bootlogo.bmp
```

**Note:** this is a BMP file

1. Simply select the image you want to use, it doesn't have to be any of the ones ive included. Just make sure it matches the pixel dimensions(640 x 480) and is **BMP** file format.
2. Rename the file to bootlogo.bmp and replace the default one in the theme at the location above.
3. Run the theme installation script again and it will set up the theme again with the new boot screen.

### 2.2. How to change the theme boot image

The boot screen for the theme is located at

```
APPS/Theme-Synthwave/res1/boot/logo.png
```

**Note:** this is a PNG file

1. Simply select the image you want to use, it doesn't have to be any of the ones ive included. Just make sure it matches the pixel dimensions(640 x 480) and is **PNG** file format.
2. Rename the file to logo.png and replace the default one in the theme at the location above.
3. Run the theme installation script again and it will set up the theme again with the new boot screen.
