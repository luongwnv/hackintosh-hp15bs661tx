# Hp 15bs661tx Opencore EFI [Supports Big Sur]
![Hp Latpop Snapshot](https://github.com/sortedcord/hp15bs661tx-hackintosh/blob/master/Docs/Laptop.png)
### Status: WIP

This repo contains information for getting macOS 11 Big Sur working on a HP 15bs-661tx Notwbook Laptop

This EFI Config now supports Big Sur as well. So if you want to upgrade you can promptly do so but I would suggest to do a fresh installation instead. Also, in case you haven't made any modifications to the laptop or have done any upgrades, I suggest buying a SATA m.2 SSD of either ~120G or ~240G as it will really help you. Trust me. It will enhance the experience if you are planning on upgrading to Big Sur.

I personally think that this i3 CPU isn't really cut out for Big Sur as I am a power user and I'd probably upgrade this laptop's motherboard with either an 8th gen i5 or and 8th ge n i7. That would really make this thing mark unto today's standards at least. Also I would recommend you to go buy the supported intel WLAN + BT card for this which can be made to work with Mac OS using intelwm. If I ever get the chance and money to make these updates I would really do so and you should also consider some of them.

As of now I think the EFI is almost complete except for a few things like DRM and stuff. (I don't have a Netflix account to use currently. If u do then please let me know) Also I think Mac OS drains the battery faster than windows but I haven't officially tested it yet. **Enhancements and improvements are always welcome**

### Currently Running:


| Component     | Version      |
| ------------- | ------------ |
| macOS version | 11.1 (20C69) |
| OpenCore      | 0.6.5        |

## Hardware Info

| Component | Model                                   |
| --------- | --------------------------------------- |
| CPU       | Intel® Core™ i3-6006U (2 GHz, 3 MB cache, 2 cores) |
| Memory    | 8 GB DDR4-2133 SDRAM (1 x 8 GB)         |
| Video Graphics [`DGPU`] | AMD Radeon™ 520 Graphics (2 GB DDR3 dedicated) |
| Storage   | Toshiba 1 TB 5400 rpm SATA              |
| Display   | 39.62 cm(15.6) diagonal FHD SVA anti-glare WLED-backlit (1920 x 1080)|
| GPU [`iGPU`] | Intel HD 520                        |
| Camera    | HP TrueVision HD Camera with integrated digital microphone |
| WLAN      | Realtek RTL8723DE 802.11b/g/n (1x1) and Bluetooth® 4.0 combo |
| Touchpad  | Synaptics SMBus Touchpad with multi-touch gesture support |
| Battery Type | 4-cell, 41 Wh Li-ion |

## Status

### Working

- [x] Keyboard (including all media keys except for brightness)
- [x] Battery indicator
- [x] Audio
- [x] Ethernet
- [x] iCloud services - iMessage, FaceTime, AppStore
- [x] GPU acceleration
- [x] Camera
- [x] Microphone
- [x] Mac-like booting interface for multiboot
- [x] Sleep/wake
- [x] Trackpad and gestures
- [x] HDMI video and audio up to 4k


### Working, sort of

- [ ] Native CPU power management. It seems that Mac OS Drains more battery than windows. Though not officially tested yet.

### Not Working at the moment
- [ ] Wifi
- [ ] Bluetooth
- [ ] Display auto brightness
- [ ] Handoff, continuity
- [ ] AirPlay

### Not Tested

- [ ] Sidecar
- [ ] FileVault
- [ ] DRM content playback (Netflix, Apple TV+)

For Networking I am mainly reliant on Ethernet and the USB WIFI dongle that I have of D-Link. Fortunately it supports Catalina (Haven't tested on Big Sur yet) but it only supports the ban standard and not ac so that's a downside. There is no way to enable bluetooth right now as I don't have a bluetooth dongle right now :(


# Old versions-
MacOSX Catalina - 1.15.7 https://github.com/sortedcord/hp15bs661tx-hackintosh/tree/catalina-1.15.7

MacOSX Mojave - 1.14.6 https://github.com/sortedcord/hp15bs661tx-hackintosh/tree/mojave-1.14.6

## CREDITS

- [Acidanthera](https://github.com/acidanthera)
- [Dortania OC guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Rehabman's battery patch guide](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/) and [Rehabman's ACPI hotpatching guide](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/)
- [CorpNewt's tools](https://github.com/corpnewt)
- [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI)