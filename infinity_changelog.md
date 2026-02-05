# Device Changelog

## 05/02/2026
- Fixed Miui Camera Icon

## 23/01/2026
- Fixed Hotspot over 5Ghz
- Nuked Display Reality Engine
- Added MiUi Color Modes (Standard,Vivid,Saturated,Original,P3,sRGB)

## 12/11/2025

- Switched to OSS Wi-Fi  
- Split 2.4GHz and 5GHz hotspot bands into separate toggle options  
- Upstreamed kernel to version 6.1.68  
- Dropped Core Control and HTPR  
- Fixed color flickering issue  
- Added Aperture Camera with support for 4K@60fps video recording  
- Fixed portrait mode in MIUI Camera  
- Integrated Viper4Android  
- Added OOS Dolby Audio  
- Implemented per-app thermals  
- Imported thermals from the Android 15 build  

## 05/10/2025

- Initial A16 Build
- Added Dolby
- Added HTPR (High Touch Poiling Rate)
- Added Option To Automatically Toggle HTPR for specific Apps/Games
- Fixed Flickering Blurs in Background
- Switched To Full OSS Kernel From Latest LOS Release
- Switched To Stock Vibrators
- Turbo Charging -> Charge Speed Limit
- Added Core Control
- Added HDR Control Settings

## 06/08/2025

- Made the UI smoother through overlay tweaks
- Enabled frame pacing for smoother visual performance
- Optimized Dalvik heap configuration for better performance
- Fixed VoWiFi functionality in Airplane Mode by enabling iWlan legacy mode
- Integrated AOSP USB v2 audio HAL
- Tuned ambient display to prevent burn-in
- Imported missing display property

## 13/07/2025
- Switched to OSS (Open Source) Kernel for improved performance and maintainability
- Implemented MIUI-style color profile modes
- Fixed color flickering issues
- Resolved Turbo Charge (18W) not working for some users
- Fixed Wi-Fi wakelock causing idle battery drain
- Removed 30Hz refresh rate mode entirely
- Fixed adaptive refresh rate behavior
- Battery charge ETA now displays correctly
- Reverted back to previous thermal implementation as newer ones were causing heating

## 06/07/2025
- Tweak Thermal a bit
- Import prebuilt kernel 6.1.78
- Import Vendor Blobs from HyperOS EEA
- Fix WPA3/WiFi6

## 08/05/2025
- Dropped Per-App Thermal Profile (was causing inconsistency and conflicts with Thermal Profile QS Tile)
- Added UDFPS Customisation Back
- Added Display Saturation Manager

## 04/05/2025
- Nuked Display Engine
- Added Dirty GPU fix and new thermal profiles (@luxured)
- Implemented new AIDL fingerprint solution (@rio113)
- Disabled "Lift to Check" by default
- Relaxed Auto-Brightness adjustment (@rio113)

## 21/04/2025
- Fixed High Touch Sampling Rate
- Reverted to usual implementation of refresh rate settings (allows switching between 60/90/120 Hz directly from Display Settings)
- Added Turbo Charging Wattage Limiter in XiaomiParts
- Switched to AIDL fingerprint instead of prebuilt  
  → Fixed Screen-off FOD for Goodix users; FPC users will retain the same experience as earlier builds.

