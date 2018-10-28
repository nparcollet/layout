# Overview

Base filesystem layout for standard cookie profiles. It defines various directories that are needed
and set several configuration files to ensure the system will properly boot. In addition, it setup
various services that are needed by the standard profiles.

# Services

- A standard init process with inittab
- Environment setup for console access
- Automatic network configuration
- Automatic USB device mounting in /media
- Telnet service
- Dropbear (SSH) service
