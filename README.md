# How to install VirtualBox & Kali Linux on Windows - Step by Step

| Last update: 07/09/2022

## WARNING : The following links will download files automaticaly, so only click on it from where you are going to install it! 

1- Download VirtualBox: 

   * For Windows: https://download.virtualbox.org/virtualbox/7.0.2/VirtualBox-7.0.2-154219-Win.exe

2- Download the extensions pack: 

   * https://download.virtualbox.org/virtualbox/7.0.2/Oracle_VM_VirtualBox_Extension_Pack-7.0.2.vbox-extpack

3- Download kali Linux: 

   * https://kali.download/virtual-images/kali-2022.3/kali-linux-2022.3-virtualbox-amd64.7z

4- You must activate the Windows Subsystem for Linux. To do this, type “Windows Features” in the search bar of the Windows menu, then open, scroll down and check the box “Windows Subsystem for Linux”, then save, exit and restart your computer.

![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5- Open VirtualBox and follow instructions of installation.

6- Click “file” in the menu, and under "preferences" and then “extension”, you add the extension pack you downloaded previously.

![8](https://user-images.githubusercontent.com/64184513/175776890-4f44fdbd-97ec-4bf9-bcf1-8db3aafa4459.jpg)

7- You will need a program to extract Kali from the .zip file. 

You can download it here : [7-zip](https://www.7-zip.org/download.html)

8- Open your download folder and double click on the .zip of kali, create a folder on your desktop and extract inside.

9- Now open this folder and double click on the .vbox file (the blue one) and follow instructions.

![1](https://user-images.githubusercontent.com/64184513/196248353-103d6d04-bc9a-4e6d-96df-6a1fe4fb753c.png)

10- Open the “configuration” of your new Kali, and idealy put at least 2 CPU for perfomance purpose + 4GB RAM. (do not overpass the red line)

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)

11- Under “network” section, set the “Attached to” to “Bridge Adapter” and randomize the Mac address.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12- Exit the setting pannel.

13- Start Kali, you will arrived on the login screen:
```
Username: kali
Password: kali
```
## Congrats, you got it. To continue further : [Learning Kali Step by Step with Self-Way](https://github.com/NeverWonderLand/Self-Way)

