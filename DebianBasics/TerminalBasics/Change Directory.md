Change directory is the command cd in Linux it is used to navigate the file system through the terminal. It is one of the most fundamental and basic commands in order to use Linux effectively.

---
Typing in the terminal 
```bash
cd
```
by itself will always move the user to the home directory

---
Adding a path for example:
```bash
cd ~/Desktop
```
will move the user to the directory specified

----
Some additional info:

cd ~/example moves the user to a directory relative to the home directory for example 
```bash
cd ~/Desktop
```

on the other hand
```bash
cd Desktop 
```
will only work if you are already in the home directory 

Moving back a directory
```bash
cd ..
```
if for example you are in ~/Desktop/Tests this will take you back a directory so to ~/Desktop

----
Relative Vs Absolute paths

A relative path is 
```bash 
cd Desktop
```
it moves you to a directory relatively to where you are currently 

An absolute path on the other hand
```bash
cd ~/Desktop
```
moves you relative to the home directory so even if you are in another directory it will always move you to a directory in the home directory 

---
In case you did not install everything in one directory there are 2 directories you have to know about not just the home directory.

1. ~/ which is the home directory 
2. / which is the root directory 

But I do recommend especially for beginners to install everything in one directory during their systems installation. I am by no means an expert but in my experience with Linux it makes things easier.