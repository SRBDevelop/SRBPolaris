# SRBPolaris V3.5 - BIOS editor for RX 460/470/480, RX 460/470/580 video cards.

- Copy memory straps fast and easy
- Set default GPU and MEM clocks
- Set GPU voltage
- Memory timing strap editor
- Unlock RX460 additional shaders

[Download SRBPolaris BIOS editor for RX](https://github.com/SRBDevelop/SRBPolaris/)
-------------------------------------------------
## How to Start

### Step 1 - Download the program

Official sources for download only.

### Step 2 - Configure the program

Open the BIOS file of your video card.

![4](https://user-images.githubusercontent.com/127048730/222979059-e678be95-6a88-498e-89f9-01d9a1c740f5.png)

![5](https://user-images.githubusercontent.com/127048730/222979068-5fed331d-9378-4d5d-9d82-e5c9d61cb39f.png)

### Step 3 - Start flashing Bios

You have now successfully completely modified your Polaris graphics card and reduced the voltage.

## Program description

Such a program provides the ability to flash video cards, which guarantees you subsequently stable operation without interruptions and other problems. This is necessary to increase the performance of a gpu in mining and not only.

Variety of cards are supported: from and to RX580.

### The main features of SRBPolaris are:

    unlocking the backup shaders;
    Copy memory straps fast and easy
    copying / editing time periods of work,
    Memory timing strap editor - make your own custom straps
    Unlock RX460 additional shaders
    Set GPU voltage
    Set default GPU and MEM clocks
    Lot’s of useful stuff

This program is considered convenient, easy to use, and, importantly, it is more suitable for beginners or those who are busy with other things, and who has no time to delve deeply into something and study.

Acceleration of the video card is achieved by changing the initial settings in the BIOS of the video card, which are used by the operating system and application programs that are read during the initialization of the equipment immediately after turning on the computer.

The firmware of video cards for mining gives a significant increase in performance, for example, the flashed RX 570 gives out 30-40% higher speed when mining, in contrast to the non-flashed version. Bypassing the firmware of video cards, you will most likely need to improve the drivers of the operating system.

After flashing, it is extremely simple and convenient to monitor and control the characteristics of the video card using the GPU-Z and HWinfo programs, the main task of which is to demonstrate the voltage, frequencies, load on the video card and many other information that will be extremely useful.

Overclocking can be easily checked in HWinfo by monitoring video memory errors. With a large number of these errors, it is necessary to reduce overclocking by decreasing the operating frequency of the video memory or flashing less aggressive timings.
SRBPolaris Won’t Start?

The program requires .NET Framework 3.5 (includes .NET 2.0 and 3.0): https://www.microsoft.com/ru-ru/download/details.aspx?id=22

## What's new ?

Latest and last ver. : V3.5
- Removed donation so no more waiting
- Added support for a few more cards
- This is the last version, happy modding

V3.2
- Added support for bioses that have 3 types of memory
- Added more options in VDDCI dropdown box

V3.1
- Added option for setting `Vddc state flag` (state pointer) , in some cases changing this value can help you change the voltage
- Added support for a few more cards

V3
- RX460 additional shaders unlocker
- Added support for Sapphire RX460 2G and 4G cards
- Added support for Sapphire RX560 2G and 4G cards

V2.65
- Added support for PowerColor RX460 2G
- Fixed a bug with VDDC pointer change

V2.64
- Added support for PowerColor RX560 4G
- Added support for Xfx RX560 4G
- Added support for Msi RX560 4G

V2.63
- Added support for a few more cards
- Added some tips for voltage manipulation

V2.62
- More efficient way of finding vddc pointer
- Fixed a bug when vddc editing

V2.61
- Added support for RX 460/560 Baffin cards
- Added support for NCP81022 VRM
- Added support for a few 4XX/5XX cards

V2.6
- Editable options: VendorID, DeviceID and Subsystem VendorID
- Added 'Small power limit' option to Powertune
- Added 'Clock stretch amount' option to Powertune

V2.56
- Added support for ASUS Expedition RX570
- Added support for XFX RX580 GTR
- Added more selections for VDDC dropdown

V2.55
- Some bug fixes
- Added more VDDCI voltages to voltage modification type

V2.53
- Added support for ASUS RX470 8G
- Added support for XFX RX580 8G
- Added support for SAPPHIRE PULSE RX580 4G

V2.52
- Added support for SAPPHIRE PULSE ITX RX 570 4G
- Added support for MSI RX570 ARMOR 4G OC
- Added support for HIS RX570 4G
- Changed manufacturer detection code

V2.51
- Added support for Sapphire RX570 4G Pulse
- Added support for MSI RX570 ARMOR 4G OC
- Added length (in bits) displayed next to every field in strap editor

V2.5
- Added memory timing strap editor (BETA)
- Added support for Asus RX570 4GB cards

V2.41
- Added support for XFX RX570 4GB cards
- Added support for editing unknown bios files (except def.frequencies and voltage)

V2.4
- Added two modification types for voltage modification

V2.3
- Added experimental support for RX5XX cards
- Added option for target temperature setting
