# Installation

## Disclaimers

---

### Goal

This is a guide for users who own a SolarPath+. The aim is to help how to efficiently use this product. 

---

### Philosophy

We do NOT sell any product or service. We do not earn money for our products. We release the guides for the new users to help build their own system and install the required programs and packages. Our only aim is to release freedom on both software and hardware. 

---

## Requirements

### System

1- There is no matter if you run the program on a different operating system but we release scripts and guides on Windows, macOS, Linux and BSD operating - systems. You can create your own script for building and add documentation. 
2- Also, here are the operating systems we recommend: 
- Windows -> Windows 10 or higher.
- macOS -> Big Sur or higher.
- Linux -> Debian 12 or higher, Fedora 43 or higher, openSUSE 15.6 or higher, Slackware 14.2 or higher, RHEL 8 or higher, Arch Linux and the distributions that based on these.
- BSD -> FreeBSD 15.0 or higher, NetBSD 10 or higher, OpenBSD 7.8 or higher. 

---

### Extra Helpful Statements

The shell scripts install the packages automatically instead of you. This will be helpful for Slackware and BSD users. 

---

### Contributing

We will start accepting contributions and collaborations starting from July, 2027.

---

### Packages

We use C++ and Fortran on administrator panel. All of the software that belongs to SolarPath+ will run locally and p2p. Just because there will not be a server between the devices and the users, you will have to maintain your system. You can check the packages inside the folder that hash the name of the operating system that is installed on your PC. You should chase for the code under the command line: "Packages". Using ctrl + f will be ĥelpful.

---

REMINDER: The only thing you will have to do is to run the build.sh/build.bat file after cloning the repository. If you are not curious, you do not have to read a script or run every script one by one. But you may have to change someting if something does not work properly. 

---

### The Main Problems You May Encounter
1- Packages
- The scripts use static package names. If you do not use the distribution but one based on another, the package names may be different on the different repositories that are on different operating systems or it may be because of the release differences.
- You can solve this problem by searching the accurate name of the package by using a command that is compatible with your distribution's package manager. 
- EX: If you cannot find the package which refers to Python, you can use "zypper se python" and find the accurate name of the Python package on openSUSE. 
2- Static Paths and File Names
- If you have a file on the exact directory and has the exact name that was chosen inside the shell script, it will override your old file or throw an error. 
- You can solve this problem by changing the names or the directories not only inside of the shell scripts but in the source code as well. This is one of the other reasons why we do not release binary blobs but release scripts for intallations. 
- We will also try to solve this problem from the repository side for users not to struggle changing the names manually. There are two correct solutions here. 