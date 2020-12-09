# m1-kali-linux-umt - amd64 image
Workaround for running Kali Linux on Apple M1 - 1. UPDATE (08.12.2020)

**Installing Kali Linux (amd64 Image) on Apple M1 (tested with MacBook Pro)**

Tested at 08.12.2020 
Tutorial by Teodor Cucu
## (if the arm version of kali linux get patched for M1 go for it!)



## **Go support @utmapp for developing UTM ([https://github.com/utmapp/UTM](https://github.com/utmapp/UTM))**



**(The GUI of Kali Linux is a bit laggy, but it works) If it's to laggy for you, install it without GUI**


Install the latest version of UTM from Github ([https://github.com/utmapp/UTM/releases](https://github.com/utmapp/UTM/releases))

Download the latest amd64 kali linux installer (Kali Linux 64-Bit (Installer)
[https://www.kali.org/downloads/](https://www.kali.org/downloads/)

After installing it, open it and create a new VM Machine:
- Change the Name to Kali Linux
- Change the Style to Operating System
- And you can choose as icon the kali linux one

![enter image description here](https://i.ibb.co/gJ0FdMy/Bildschirmfoto-2020-12-08-um-17-21-56.png)

Go to the System Tab and choose the following Options:
- Archictecture = x86_64
- System = Standard PC (i440FX + PIIX, 1996)
- 4GB RAM

![enter image description here](https://i.ibb.co/yYtpyH4/Bildschirmfoto-2020-12-08-um-17-22-07.png)

Now we are going to the “Drives” Tab. We create a new Drive, in order to install Kali Linux on it. For this choose New Drive and as interface VirtlO.

![enter image description here](https://i.ibb.co/FWpCXDD/Bildschirmfoto-2020-12-08-um-17-22-45.png)

After this we need to import a drive (in our case, we choose the kali-linux iso that we previous downloaded).

![enter image description here](https://i.ibb.co/BVmNqZ5/Bildschirmfoto-2020-12-08-um-17-23-12.png)

After adding it, go sort the iso as first boot (up-down arrows under Interface) like in this picture

![enter image description here](https://i.ibb.co/FJ64HKW/Bildschirmfoto-2020-12-08-um-17-25-08.png)

And that’s all, go boot the system and you can install it ;).

If you don't know how to install kali linux, check this link out:
https://www.kali.org/docs/installation/hard-disk-install/


![enter image description here](https://i.ibb.co/PN77vJt/Bildschirmfoto-2020-12-08-um-00-16-00.png)
