# legion-go-bios
archive of bios files

## Downgrade BIOS instructions
To access the BIOS menu on the Lenovo Legion Go 8APU1, ensure the device is off. Press and hold the volume up button and then turn on the device. You can release the volume up button once you come to a screen the allows you to select BIOS Setup. You may need to use the touchscreen instead of the touchpad.

Navigate to More Settings > Configuration. Scroll down to find BIOS Back Flash. Once enabled, you can flash the BIOS to any previous or current version. Press Back in the top left corner once you've enabled the setting, then Exit in the top right. Make sure to Save and Exit to preserve your setting changes.

| BIOS Version | Release Date |
| ----------- | ----------- |
| n3cn22ww | 07 JUL 2023 |
| n3cn23ww | 09 NOV 2023 |
| n3cn26ww | 22 NOV 2023 |
| n3cn28ww | 05 DEC 2023 |
| n3cn29ww | 05 DEC 2023 |
| n3cn31ww | 28 MAR 2024 |
| n3cn32ww | 19 APR 2024 |
| n3cn35ww | 19 JUL 2024 |
| n3cn37ww | 14 FEB 2025 |
| n3cn38ww | 29 MAY 2025 |
| n3cn39ww | 19 AUG 2025 |
| n3cn40ww | current |

Translated release note information (rough translation)

Update Notes:

## < N3CN39WW>
- (Fix) Added patch


## < N3CN38WW>
- (Fix) Added patch


## < N3CN37WW>
- (Fix) Updated AMD PI to 1.1.8.0
- (Fix) Added patch
- (Fix) Resolved DUT boot hang after random BIOS updates
- (Fix) Updated PD firmware


## < N3CN35WW>
- (Fix) Based on BIOS34 with version update only
- (Fix) Modified BT MCU wake-up timing for abnormal recovery from prolonged sleep issues


## < N3CN32WW>
- (Fix) Configuration in DC Customer Mode
- (Fix) Security update
- (Fix) Diagnostic tool update
- (Fix) Firmware update


## < N3CN31WW>
- (Fix) Release update


## < N3CN29WW>
- (Fix) Updated PI code to 1.1.0.1a
- (Fix) 2024 IPU1 security BIOS update
- (Fix) Optimized fan table interface
- (Fix) Added tool interface to limit charging percentage
- (Fix) Added auto option for UmaFrameBufferSize.
- (Fix) Fixed new standby performance test_The exit duration value to 1.137 seconds/1.139 seconds
- (Fix) Fan customization feature not working in STP/Secure Mode
- (Fix) Added interface to limit RSOC BAT, addressing issues with adding and fixing this time until full charge/discharge
- (Fixed) Resolved fan_full_on issue occurring before goto window os when fanfullon feature is enabled
- (Fixed) Updated MIPI firmware to V1.2E

## < N3CN28WW>
- (Added) Implemented STAMP/STT thermal mode toggle
- (Added) Added memory frequency toggle between 6400 and 7500 MHz
- (New) Added charging speed optimization option, allowing users to select charging speed under high load
- (New) Provided USB-C port compatibility option, supporting more USB high-power devices
- (New) Added 6GB VRAM option
- (New) Supported Lenovo fan table adjustment interface
- (New) Supported Lenovo sPPT/fPT tuning interface
- (Fixed) Resolved several performance issues
- (Fixed) Addressed VRAM option functionality failure
- (Fixed) Miscellaneous fixes


## < N3CN26WW>
- (Fixed) Restored TF cards lost in Genesys SD card reader during MS recovery
- (Fixed) Renamed


## < N3CN23WW>
- (Fixed) Updated Legion Go icon in settings page
- (Fixed) Updated MIPI firmware to V1.2D


## < N3CN22WW>
- (New) First release

Translated with DeepL