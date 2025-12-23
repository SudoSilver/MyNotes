The apt is the package manager inside of Debian, Ubuntu and Linux Mint and this is where we have a difference with other Linux Distributions.

I will not explain other package managers as I don't feel like I am currently experienced enough to talk about them.

All actions that using apt require [[Root Privilege]] or [[Sudo]]  

---
Apt update refreshes the repositories and checks for any updates to the software we have currently installed using apt.
```bash
sudo apt update
```
Typically you want to run this command at least once per day.

---
In case we have any updates to do after running the apt update command we actually install the updates using apt upgrade.
```bash
sudo apt upgrade 
```
We also want to run this at least once a day.

---
To install any software using the apt package manager we use apt install and then the name of the package we want to install exactly as it is in the apt repositories in this example we are installing git.
```bash
sudo apt install git 
```

We can also install multiple packages at once.
```bash
sudo apt install git vim 
```

---
If we do not know how a package is named in the apt repositories we can search for it using:
```bash
sudo apt search git
```
This will search for any packages inside of the apt repositories that contain the word git in their name as an example.

NOTE: search doesn't require [[Root Privilege]] or [[Sudo]] to run but said privileges with every apt action creates consistency and avoids confusion for beginners.  

---
To uninstall packages that have been installed with apt we run:
```bash
sudo apt purge vim
```
In this case we uninstall vim but a package might have some dependencies we no longer need after removing said package so we run
```bash
sudo apt autoremove
```
to remove said dependencies.

---
apt is typically the recommended way to install packages as it is secure and every package in it is reviewed but it can contain outdated versions of software 

In case you have [[Root Privilege]] there is no need to prefix apt actions with sudo 

