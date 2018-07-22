# Changing the package manager

### Temporarily (On Linux, BSD, and macOS.)

To Temporarily change the package manager used, use an argument. For example, if I wanted to temporally change it to apt-get, I would type

    sudo termget apt-get

### Permanently (On Linux, BSD, and macOS)
Run the following command in a terminal, then the first setup script will start next time you run termget.

If you are running a version of TermGet after 2.1.0 run (as root):

    rm /usr/local/share/termget/termget-package-manager && > /usr/local/share/termget/termget-package-manager

If you are running a version of TermGet before 2.1.0 run:

    rm ~/.termget/termget-package-manager && > ~/.termget/termget-package-manager