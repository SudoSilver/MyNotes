Removing files and/or directories on Linux is very simple using the *rm* command.
*rm* is fairly universal in Linux and it works relatively the same in Debian, Ubuntu, Linux Mint and Arch.

---
To remove a basic file for example file.txt we can do:
```bash
rm file.txt
```
Which typically is enough to remove any file.

---
But the more reliable way is to run it with [[Root Privilege]] or [[Sudo]] and follow it with -rf
```bash
sudo rm -rf directory 
sudo rm -rf file.txt
```
Breaking this down we first give it elevated privilege with [[Sudo]] or by being [[Root Privilege|Root]] then we tell it to remove recursively and forcefully so we ignore nonexistent files or directories. 

BUT giving it [[Root Privilege]] or [[Sudo]] is dangerous and unnecessary most of the time.
```bash
rm -rf directory
rm -rf file.txt
```
With NO [[Root Privilege]] or [[Sudo]] is sufficient for any file owned by the current user and should be preferred especially if you are new to Linux. 