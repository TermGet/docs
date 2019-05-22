---
layout: default
title: Usage
nav_order: 8
---

# Usage

This section gets updated with every release. If you are using an alpha or beta build, there might be extra features that aren't in this section of the docs.

TermGet is really easy to use. To run it, all you have to do is open a terminal window, and type:

    sudo termget

Once your package manager has been chosen, you will get a message like this:

    Please choose an action

    1. Search for packages
    2. Install a package
    3. Remove a package
    4. Update all packages
    5. Update Database
    6. Clean
    7. Credits
    8. Exit
    9. Enter bash

*We will be using "eopkg" in the examples below.*
*Results may vary for other package managers*

### Searching for Packages

Search, searches for packages.

If are using TermGet 3.0, it will ask "Did you find what you were looking for?". If you type y (For yes), then it asks you for the package to install (just in case the package you were looking for had a slightly different name then you thought). Once you type the name of the package it will install the package.

### Installing a package

Installing a package downloads and installs the package.

### Removing a package

Removing a package uninstalls a package.

### Updating all packages

Updating all packages updates EVERYTHING ON THE SYSTEM.

### Updating the repository

Updating the repository, checks the repository for new versions of packages. It is recommended to do this before updating.

### Cleaning

Cleaning helps save hard drive space. It does this by deleting cache, and deleting unneeded dependencies.

### Entering the Shell

If you want to run a shell command like to add a PPA or something like that, you can open the shell and run the command, then type ```exit``` or press CTRL-D to leave the shell, and go back to TermGet.

# Using third-party package managers...

### Flatpak

If you would like to install flatpak packages with TermGet, run:

```termget flatpak```

Note: The only source flatpak will install from is Flathub.

### Snap

```termget snap```

### Using PIP

```termget pip```

or

```termget pip2```

or

```termget pip3```

### Using APM

```termget apm```

### Using NPM

```termget npm```

### Using Yarn

```termget yarn```

### Using Bower

```termget bower```

### Using GEM

```termget gem```

### Using NIX

Nix is usually used for NixOS, however it can be installed on other distros, as well as macOS...

```termget nix```
