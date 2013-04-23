plymouth-theme-ubuntu8
======================

A plymouth theme in style of windows 8 boot progress

Installation instructions
=========================

```bash
sudo cp -r plymouth-theme-ubuntu8 /lib/plymouth/themes/ubuntu8
sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/ubuntu8/ubuntu8.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
```
Logo choosing
=============

You can choose between 2 different logo's to use.
![logo1][logo.png] default
![logo2][logo_other.png] more windows 8 like

To change to the second logo, rename logo_other.png to logo.png and that's it!

screenshot
==========
![screebshot](screenshot.png)
