# How to install Kali Linux in VirtualBox on Windows - Step by Step
-----------------------------------------------
- Last update: 24/06/2022

- NOTES: The following links will download files automaticaly, so only click on it from where you are going to install it! 
----------------------------------------------  
1- Download VirtualBox: https://download.virtualbox.org/virtualbox/6.1.34/VirtualBox-6.1.34a-150636-Win.exe

2- Download the extensions pack: https://download.virtualbox.org/virtualbox/6.1.34/Oracle_VM_VirtualBox_Extension_Pack-6.1.34.vbox-extpack

3- Download kali Linux: https://kali.download/virtual-images/kali-2022.2/kali-linux-2022.2-virtualbox-amd64.ova

4- You must activate the Windows Subsystem for Linux. To do this, type “Windows Features” in the search bar of the Windows menu, then open, scroll down and check the box “Windows Subsystem for Linux”, then save, exit and restart your computer.

5- Open VirtualBox and follow instructions of installation.

6- Click “file” in the menu, and under “extension”, you add the extension pack you downloaded previously.

7- Click “file” in the menu again, then click on “Import Appliance”.

8- Select the Kali you downloaded (.ova file) and click on continue.

9- Let the option “create new .vdi” and the “dynamic storage” like they are BUT put at least 80 GB of storage.

10- Click on “import”

11- Open the “configuration” of your new Kali, and idealy put at least 2 CPU for perfomance purpose + 4GB RAM. (do not overpass the red line)

12- Under “network” section, set the “Attached to” to “Bridge Adapter” and randomize the Mac address.

13- Exit the setting pannel.

14- Start Kali, you will arrived on the login screen:
Username: kali
Password: kali

---------------------------------------
## Starting With Kali Linux - Step by Step

- Now that you are in your new machine, click on the menu and open a ROOT terminal (the red one)
password: kali

type this command;

    apt-get update && apt-get upgrade -y
- Now we will continue on this page!
https://github.com/NeverWonderLand/no-more.git
