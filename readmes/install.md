# How do I install TermGet on Linux, BSD, and MacOS

### Installing Python3

To install TermGet, we need to install python3. To check ot see if it's already installed type:

    python3 --version

Install off your operating system's respository.
If you on MacOS, download it from https://python.org

After you install python3, download TermGet.

Before you run the install TermGet there are some OS specific dependencies.

### Arch Linux Dependencies

If you are on Arch Linux, you need to install yaourt in order to use the AUR. To do this, open a terminal and type:

    git clone https://aur.archlinux.org/package-query.git
    cd package-query
    makepkg -si
    cd ..
    git clone https://aur.archlinux.org/yaourt.git
    cd yaourt
    makepkg -si
    cd ..

### Mac OS Dependencies

If you are on Mac OS, you need to install Homebrew. To do this open a terminal and type:

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


### Downloading and Installing TermGet

Now we need to download TermGet

Go to the download page for TermGet and download it.

Extract TermGet somewhere and open a terminal window.

Now set your current directory in the terminal to the extracted TermGet folder, (example: ```cd ~/Downloads/TermGet-2.1.3```)

Now type:
    
    ./install.sh

If you want to run the install script without detection of the package manager, there is a mode for that:

    ./install.sh --no-detection
    
The above command can be used if the package file already exists from an older build of TermGet. It can also be used if you want TermGet to directly ask you what package manager you would want to use.