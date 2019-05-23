---
layout: default
title: First Time Setup
nav_order: 7
---

# First Time Setup

After installing, run TermGet using:

    sudo termget

If you installed TermGet without detection of the package manager, or package manager detection failed, this message will come up:

    Please choose a package manager:
    
    1. apt-get (For Debian, and Debian based systems.)"
    2. dnf (For Fedora, and Fedora based systems.)"
    3. yum (For RHEL, CentOS, older versions of Fedora, and systems based on these distros.)"
    4. pacman (For Arch, PacBSD, and systems based on these distros.)"
    5. zypper (For OpenSUSE, and OpenSUSE based systems.)"
    6. eopkg (For Solus, and Solus based systems.)"
    7. emerge(For Gentoo, and Gentoo based systems.)"
    8. xbps (For Void Linux, and Void Linux based systems.)"
    9. pkg (for FreeBSD, and FreeBSD based systems.)"
    10. homebrew (for macOS/OS X)"
    11. chromebrew (for Chrome OS, Chromium OS, CloudReady, NayuOS, and other systems based on Chromium OS.)"
    12. nix (For NixOS, and NixOS based systems.)"

Choose your distribution's package manager using the number. For example, if your package manager is dnf, you would type ```2``` and press ```Enter```.

If you are on macOS type ```10``` for homebrew.
If you are on ChromeOS type ```11``` for chromebrew.
