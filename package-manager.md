---
layout: default
title: Changing the Package Manager
nav_order: 9
---

# Changing the Package Manager

### Temporarily (On Linux, BSD, and macOS.)

To Temporarily change the package manager used, use an argument. For example, to temporally change the package manager to apt-get, you would type:

    sudo termget apt-get

### Permanently (On Linux, BSD, and macOS)

Run the following command in a terminal (as root), then the first setup script will start next time you run termget.

    rm /usr/local/share/termget/termget-package-manager && > /usr/local/share/termget/termget-package-manager
