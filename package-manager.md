---
layout: default
title: Changing the Package Manager
nav_order: 9
---

# Changing the Package Manager

### Temporarily (On Linux, BSD, and macOS.)

To Temporarily change the package manager used, use an argument. For example, to temporally change the package manager to apt, you would type:

    sudo termget apt

### Permanently (On Linux, BSD, and macOS)

Run the following command in a terminal window, then the first setup script will start next time you run termget.

    su -c rm /usr/local/share/termget/termget-package-manager && > /usr/local/share/termget/termget-package-manager
