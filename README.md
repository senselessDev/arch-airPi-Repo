# arch-airPi-Repo

This repository contains all Arch Linux packages that i created for using the Raspberry Pi as an HD-Digital-FPV-Cam.

## how to use

To get access to the packages in this repository, you have to tell pacman where to find them in your `/etc/pacman.conf`. 

Open the file in your editor of choice and append the following lines:
```
[airPi-Repo]
Server = https://github.com/senselessDev/arch-airPi-Repo/raw/master/
```

Now you have to download a fresh copy of the package list by invoking  `pacman -Sy`.

After doing that, you should be able to install any package of this repository. For example you can install the basic [airPi-Package](https://github.com/senselessDev/arch-airPi-Package) with `pacman -S airPi`.
