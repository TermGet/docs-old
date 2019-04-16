# Changing the package manager

### Temporarily (On Linux, BSD, and macOS.)

To Temporarily change the package manager used, use an argument. For example, if I wanted to temporally change it to apt-get, I would type

    sudo termget apt-get

### Permanently (On Linux, BSD, and macOS)

Run the following command in a terminal (as root), then the first setup script will start next time you run termget.

    rm /usr/local/share/termget/termget-package-manager && > /usr/local/share/termget/termget-package-manager