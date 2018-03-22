# ubuntu-lamp

This Vagrantfile includes an inline shell provisioning block that will install the dependencies for a basic LAMP stack.
Download a zip here, or use git to clone this repository to your local system.

Once you have satisfied the dependencies (below), unzip (if applicable) and navigate to the ubuntu-lamp directory in your terminal; execute `vagrant up`.

When completed successfully, you should see the following output in the terminal:

    Basic LAMP dependencies are now installed.
    Browse to apache using localhost:8888 or 192.168.222.222
    Use 'vagrant ssh' to login via terminal.
    MySQL username:password root:root; invoke using 'mysql -uroot -p'


## Requirements for vagrant
Download and install virtualbox and vagrant, making sure that virtualization is supported on your system.

You may have to restart after installing these.

### virtualbox
From Oracle; provides virtualization.

Get the installer from Oracle https://www.virtualbox.org/

Tested with version 5.1.34 r12 1010 (Qt5.5.1)


### vagrant
At the simplest, a convenience wrapper around a virtualization provider.

Get the installer from the official site https://www.vagrantup.com/

Tested with version 2.0.3

### terminal
You will need a terminal/console/shell to invoke vagrant. Provided with most OS.
If powershell is incompatible, try 'git bash' https://git-scm.com/download/win.
