# WuWa Config Extractor

An Android application designed to safely and easily extract configuration files for Wuthering Waves into the restricted Android/data directory using Shizuku.

## Screenshots

| Main Screen | Extraction Progress |
|:-----------:|:-------------------:|
| ![Main Screen](./screenshots/Screenshot_1.jpg) | ![Extraction Progress](./screenshots/Screenshot_2.jpg) |

## Features

- **Direct Extraction**: Extract ZIP configuration files directly to com.kurogame.wutheringwaves.global/files/UE4Game/Client/Client/Saved/Config/Android.
- **Shizuku Integration**: Leverages Shizuku for root-less access to restricted system directories.
- **Online Presets**: Download and apply pre-configured optimizations directly from the official repository (https://github.com/rdevz-ph/wuwa-configs).
- **Chipset Compatibility Check**: Automatically verifies if a configuration ZIP (containing chipset.txt) is compatible with your device's hardware before extraction.
- **Detailed Logging**: Real-time feedback and logs for the extraction process.
- **Overwrite Protection**: Option to overwrite existing files or skip them.

## Requirements

1. **Shizuku App**: You must have the Shizuku app installed and running on your device.
2. **Permission**: Grant Shizuku permission to this app when prompted.
3. **Android 8.0+**: Minimum supported version is Android 8.0 (API 26).

## How to Use

1. **Start Shizuku**: Ensure the Shizuku service is running via Wireless Debugging or ADB.
2. **Select Config**:
   - Choose a preset from the Online Presets dropdown.
   - OR tap Select ZIP File to pick a custom configuration from your storage.
3. **Check Compatibility**: The app will automatically detect your chipset and check it against the ZIP's requirements.
4. **Extract**: Tap Extract Files. The app will handle the rest.

## Creating a Compatible ZIP

To support the compatibility check, add a chipset.txt file to the root of your ZIP with supported model codes (e.g., mt6877 for Dimensity 900). 

## Disclaimer
> [!WARNING]
> **WuWa Config Extractor** is an independent tool created for educational and personal use only.  
> It is **not affiliated with, endorsed by, or connected to Kuro Games** in any way.
>
> - All trademarks, game assets, and intellectual property belong to their respective owners.
> - This tool modifies configuration files of *Wuthering Waves*. **Use at your own risk.**
> - The developers assume no liability for any account bans, data loss, or device issues resulting from the use of this software.
> - Always back up your original configuration files before making changes.
>
> By using this application, you acknowledge that you are solely responsible for any consequences.

## License

This project is licensed under the [MIT License](LICENSE).
