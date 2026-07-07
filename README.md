# TLP
TLP is a comprehensive power management solution for Linux laptops. Unlike manual sysfs
tuning, TLP applies a coordinated set of optimizations automatically whenever the power source
changes - AC or battery. It handles CPU governors, disk APM, PCIe ASPM, USB autosuspend,
radio devices, and more through a single configuration file.


# Ubuntu has basic power management through upower and systemd, but TLP adds:
  Automatic per-device power management
  Different settings for AC vs battery
  Battery charge thresholds (for compatible hardware)
  Coordinated application of many settings at once
  Per-device exceptions
