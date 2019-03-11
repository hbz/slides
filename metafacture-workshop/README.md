# Metafacture-Workshop

## To set up your machine

* Get the workshop data: [https://github.com/hbz/metafacture-flux-examples/archive/workshop.zip](https://github.com/hbz/metafacture-flux-examples/archive/workshop.zip)
* Set up Metafacture on the command line: [https://github.com/metafacture/metafacture-core#metafacture-as-a-stand-alone-application](https://github.com/metafacture/metafacture-core#metafacture-as-a-stand-alone-application)
* Install the Metafacture IDE: [https://github.com/culturegraph/metafacture-ide/blob/master/MANUAL.textile#installation](https://github.com/culturegraph/metafacture-ide/blob/master/MANUAL.textile#installation)

## Alternatively, you can use VirtualBox


As an alternative to the manual setup above, we provide a working environment for VirtualBox. VirtualBox is available for all OSes and allows to run a virtual computer in your own OS. The virtual machine provides every tool mentioned under "Local installation", set up as a Linux box.

### Installation of VirtualBox

See: [https://www.VirtualBox.org/wiki/Downloads](https://www.VirtualBox.org/wiki/Downloads)

Start the box. If it doesn't come up with a GUI you may have to install the "virtualbox-qt" package.

### Load the virtual machine into VirtualBox

Download the zipped Metafacture workshop virtual machine from [http://labs.lobid.org/download/](http://labs.lobid.org/download/). The size of the packed file is 3 GB, unpacked it's 7.5 GB (so make sure you have got around at least 10 GB free space). Decompressing takes about 5 minutes, depending on your hardware. To set it up in your VirtualBox:

- Menu -> Machine -> Add...
- Select the `.vbox` file you downloaded and unzipped

When you are finished, a virtual machine should appear in the VirtualBox. Start the machine. A new window should appear with Ubuntu booting until you see the graphical login manager. If you get a "kernel panic" instead, try to [enable virtualization in your BIOS or EFI](https://www.howtogeek.com/213795/how-to-enable-intel-vt-x-in-your-computers-bios-or-uefi-firmware/).

### Configs of your virtual machine

The password for the user _I_ is "12345".

*Note*: the keyboard-layout is preconfigured to German. If you want to change this: click on the blue-white icon in the top left corner under "machine", choose "settings" on the right bottom, select "Keyboard" on the left side. Click on the "Layout" tab, unclick the "Use system defaults", "Add" the keyboard layout you need, then push it to first position by selecting that layout and clicking on the arrows. Close the window, you are done.

Normally it's possible to copy 'n' paste between your "normal" OS (aka "host") and the "guest" (the Ubuntu machine). While it's not a mandatory feature it may be handy. If that's not working and you feel you need it: you need to install the ["Guest Additions"](https://www.virtualbox.org/manual/ch03.html#settings-general-advanced).
