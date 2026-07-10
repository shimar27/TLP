# TLP
TLP is a comprehensive power management solution for Linux laptops. Unlike manual sysfs
tuning, TLP applies a coordinated set of optimizations automatically whenever the power source
changes - AC or battery. It handles CPU governors, disk APM, PCIe ASPM, USB autosuspend,
radio devices, and more through a single configuration file.


## Ubuntu has basic power management through upower and systemd, but TLP adds:
  - [x] Automatic per-device power management
  - [x] Different settings for AC vs battery
  - [x] Battery charge thresholds (for compatible hardware)
  - [x] Coordinated application of many settings at once
  - [x] Per-device exceptions

## Plan
* Installation
* Configuration File
* CPU Settings
* Disk Settings
* USB Autosuspend
* Radio Device Management
* Battery Charge Thresholds
* Applying Configuration Changes
* Useful tlp-stat Outputs
* Troubleshooting
* Monitoring Battery Health



# Conclusion
TLP is generally set-and-forget after initial configuration. The defaults are already good for most
laptops, and customizing the charge thresholds is usually the most impactful change for long-
term battery health.
