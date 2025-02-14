# Hackintosh EFI - i7 10700k + RX 6600XT

This repository contains the OpenCore EFI configuration files for running macOS Sonoma (14.x) on the following hardware configuration:

## Hardware Specifications

- **CPU:** Intel Core i7-10700K (Comet Lake)
- **GPU:** AMD Radeon RX 6600 XT
- **OpenCore Version:** Latest stable version

## Features

- Full hardware acceleration with native AMD drivers
- All CPU cores working properly
- Native power management
- Sleep/Wake functionality
- USB ports mapped correctly

## Important Notes

- This EFI is specifically configured for the i7-10700K CPU and RX 6600 XT GPU combination
- Make sure to generate your own SMBIOS information before using this EFI
- Always backup your data before making any changes to your EFI

## Compatibility

- macOS Sonoma (14.x)
- May work with other macOS versions, but tested primarily with Sonoma

## Disclaimer

This EFI configuration is provided as-is. Use at your own risk. Make sure to:

- Generate your own SMBIOS
- Adjust BIOS settings according to OpenCore guidelines
- Keep backups of your working EFI folder

## Credits

- [OpenCore Team](https://dortania.github.io/OpenCore-Install-Guide/)
- All developers who contribute to the Hackintosh community
