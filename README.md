plymouth-theme-ubuntu8
======================

A plymouth theme in style of windows 8 boot progress

Installation instructions
=========================

~~bash
sudo cp -r plymouth-theme-ubuntu8 /lib/plymouth/themes/ubuntu8
sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/ubuntu8/ubuntu8.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
~~
