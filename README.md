# How to install Kali Linux in VirtualBox on Windows - Step by Step
-----------------------------------------------
- Last update: 25/06/2022

- NOTES: The following links will download files automaticaly, so only click on it from where you are going to install it! 
----------------------------------------------  
1- Download VirtualBox: https://download.virtualbox.org/virtualbox/6.1.34/VirtualBox-6.1.34a-150636-Win.exe

2- Download the extensions pack: https://download.virtualbox.org/virtualbox/6.1.34/Oracle_VM_VirtualBox_Extension_Pack-6.1.34.vbox-extpack

3- Download kali Linux: https://kali.download/virtual-images/kali-2022.2/kali-linux-2022.2-virtualbox-amd64.ova

4- You must activate the Windows Subsystem for Linux. To do this, type “Windows Features” in the search bar of the Windows menu, then open, scroll down and check the box “Windows Subsystem for Linux”, then save, exit and restart your computer.

![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5- Open VirtualBox and follow instructions of installation.

6- Click “file” in the menu, and under "preferences" and then “extension”, you add the extension pack you downloaded previously.

![8](https://user-images.githubusercontent.com/64184513/175776890-4f44fdbd-97ec-4bf9-bcf1-8db3aafa4459.jpg)

7- Click “file” in the menu again, then click on “Import Appliance”.

![1](https://user-images.githubusercontent.com/64184513/175776398-7038d85a-a306-4c4c-ad89-325b5c938383.jpg)

8- Select the Kali you downloaded (.ova file) and click on continue.

![2](https://user-images.githubusercontent.com/64184513/175776400-a41767db-3686-4a3b-b978-bf136286f9f0.jpg)

9- Click on “import”

![3](https://user-images.githubusercontent.com/64184513/175776402-4eff95b8-9785-47e1-9877-67df34d808e2.jpg)

10- Open the “configuration” of your new Kali, and idealy put at least 2 CPU for perfomance purpose + 4GB RAM. (do not overpass the red line)

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)

11- Under “network” section, set the “Attached to” to “Bridge Adapter” and randomize the Mac address.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12- Exit the setting pannel.

13- Start Kali, you will arrived on the login screen:
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
