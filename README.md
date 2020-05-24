# DevOps9

This vagrant will install 1 Ubuntu 18.04 machine.
It will add some default users, groups and directory's.
This Vagrant is to practice Docker and Wordpress containers.
This repository is intended for educational purpose only.


## Prerequisites

Works on Windows 10 and tested on macOS (macOS needs the Virtualbox extension pack).

Software needed:
* Virtualbox 5.0 or higher
* Git bash for Windows
* Vagrant 2.2.6 or higher


## Demo installation && use Vagrant

Youtube: https://youtu.be/KABnIuaA8SM


## Installation

* Install Virtualbox: https://www.virtualbox.org/wiki/Downloads
* Install Git bash for Windows: https://gitforwindows.org/
* Install Vagrant for Windows: https://www.vagrantup.com/downloads.html

## Run this Vagrant VM
Open **Git Bash** in Windows
```
cd Documents
mkdir vagrant && cd vagrant
git clone https://github.com/borahuho/DevOps9
cd DevOps9
vagrant up
vagrant ssh
```
## Mission

Read your mission in the directory "Opdracht".

## Network
Vagrant VM will be set up with 2 network adapters
```
Nat : DHCP
Localhost : 192.168.10.12
```
## Vagrant commands
Make a new VM with Vagrant
```
vagrant up
```
Stop and shutdown a VM
```
vagrant halt
```
Remove a VM
```
vagrant destroy
```
ssh in to the VM
```
vagrant ssh DevOps9
```

