# How do I use TermGet on Linux, BSD, MacOS, and ChromeOS

This section gets updated with every release, if you are using an alpha or beta build, there might be extra features that aren't on this section of the README file.

TermGet is really easy to use. To run it, all you have to do is open a terminal, and type:

    termget


Just select using the number (for example if my package manager was apt-get, I would type the number 1, and press enter).

Once your package manager has been chosen, you will get a message like this:

    Please choose an action

    1. Search for packages
    2. Install an application
    3. Remove an application
    4. Update all packages
    5. Update Database
    6. Clean
    7. Credits
    8. Exit
    9. Enter shell

*We will be using "eopkg" in the examples below.*
*Results may vary for other package managers*

### Searching for Packages

Search, searches for packages.

If are using TermGet 3.0 (currently in alpha), it would ask "Did you find what you were looking for?". If you type y (For yes), then it asks you for the package to install (just in case the package you were looking for had a slightly different name then you thought). Once you type the name of the package it will install the package.

### Installing a package

Installing a package downloads and installs the package.

### Removing a package

Removing a package uninstalls a package.

### Updating all packages

Updating all packages updates EVERYTHING ON THE SYSTEM. ()

### Updating the repository

Updating the repository, checks the repository for new versions of packages. It is recommended to do this before updating.

### Cleaning

Cleaning helps save hard drive space. It does this by deleting cache, and deleting unneeded dependencies.

### Entering the Shell

If you want to run a shell command like to add a PPA or something like that, you can open the shell and run the command, then type ```exit``` or press CTRL-D to leave the shell, and go back to TermGet.

### Using PIP

To run TermGet with PIP, just run:

```termget pip```

or

```termget pip2```

or

```termget pip3```.

### Using APM

To run TermGet with APM, just run:

```termget apm```

## Features in 3.0 Alpha

If you are using the TermGet 3.0 (Currently in Alpha), here are the features it adds.

### Checking for updates

This will check to see if your version of TermGet is update to date. If not, please update. (Note: This feature is only for release versions. If you are using a Alpha version, it will always say that TermGet is outdated.)

### Snap Support

If you would like to install snap packages with TermGet, run:

```termget snap```.

### Flatpak Support

If you would like to install flatpak packages with TermGet, run:

```termget flatpak```.

Note: The only source flatpak will install from is Flathub.