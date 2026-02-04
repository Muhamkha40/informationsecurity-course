## Karvinen 2021: Install Debian on Virtualbox Summary:

This text outlines guide for how to install debian linux on virtual box.

1. It starts by getting the Debian Live ISO. At the beginning it also gives some tips about how to do it on Macs. For the virtualbox setup we can  configure the VM to RAM: 4000 MB (minimum 2000 MB) which is recommended.
  
2. After booting the VM select Live Mode. Open the "Install Debian" icon on the desktop. You can also run linux from the ISO file.
  
3. During the installation process Set a "Real Name" and a short "Login Name" (lowercase only) and then choose a password.
   
4. After installing restart the machine and do some updates like sudo apt-get update, after this it is also possible to fix screen resolutions.

I am not sure but since "Skip Unattended Install" is required to avoid installation failures in the virtual box can we say that virtualBox's automation isn't yet fully compatible and developed for Debian. 

## Karvinen 2020: Command Line Basic

This is also an guide about fundamental concepts and commands for managing a Linux system.

1. For navigation CLI always operates within a working director
* for exammple `pwd`: Print Working Directory (shows where you are) and `ls`: List files in the current folder.

2. For File and Folder:
* `mkdir:` Creates a new folder.
* `rm:` Delete files, and these files are deleted for good as their are no "trash bins".
* `mv:` Move or rename files/folders.

3. Manuals and System structure:
* Most commands come with a "manual" you can read by typing `man [command]` example , `man ls`
* `/home/`: Where user data is kept.
* `/etc/`: Where system settings files are

An additional feature is `sudo:`that stands for "SuperUser Do"

4. Lastly Package Management
* this is a easy way of installing software.
* Example: `sudo apt-get update` Always run this first to refresh the list of available software.

## a) Disable networking
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/00310ff8-2f00-4ab4-b2b8-d3172bf2b018" /> 

## b) Local Port Scanning 
<img width="956" height="347" alt="Screenshot 2026-02-04 at 16 23 46" src="https://github.com/user-attachments/assets/89351cfa-71f8-4cbe-a1ec-16afb7d4aac9" />

## c) Daemon scan 
<img width="851" height="329" alt="Screenshot 2026-02-04 at 16 38 49" src="https://github.com/user-attachments/assets/8572dd12-5cea-4af4-b8c1-b3325548202c" />

## d) Levels with passwords
- Level 0
<img width="983" height="516" alt="Screenshot 2026-02-04 at 17 44 52" src="https://github.com/user-attachments/assets/7ce02572-80e1-4966-9ce2-db6f51ae07fc" />

- Level 0 --> 1
<img width="2048" height="1152" alt="image" src="https://github.com/user-attachments/assets/da5dfeef-4cac-4fd8-8aa9-61e1c3aa7ed2" />

- Level 1 --> 2
<img width="817" height="252" alt="Screenshot 2026-02-04 at 17 46 10" src="https://github.com/user-attachments/assets/03108d6c-fc7d-4f97-b28d-e9cadd6aa97a" />

- Level 2 --> 3
<img width="1012" height="369" alt="Screenshot 2026-02-04 at 17 46 40" src="https://github.com/user-attachments/assets/482bdfd7-c0e2-4a6c-9274-d9eeba2fe3a5" />

- Level 3 --> 4
<img width="554" height="430" alt="Screenshot 2026-02-04 at 17 47 21" src="https://github.com/user-attachments/assets/600cb2c2-8c59-48a0-9c14-a6c182175387" />

## Sources: 
- https://terokarvinen.com/2020/command-line-basics-revisited/ 
- https://terokarvinen.com/2021/install-debian-on-virtualbox/
- https://overthewire.org/wargames/bandit/








