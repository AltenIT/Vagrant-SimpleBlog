# Test-Development Environment in Vagrant
A Vagrant based virtual environment for the Springmvc-Shoppingcart demo application (Alten Java for Testers programme).

## Todo
- [x] Change from Debian to Ubuntu
- [x] Add docker support to image
- [ ] Add Sonarcube
- [ ] 1st time config of Jenkins
- [x] Add Postman
- [x] Show desktop icons


# Instructions for getting started with Vagrant
## Prerequisites
- Oracle VirtualBox https://www.virtualbox.org/
- Vagrant https://www.vagrantup.com/downloads.html

## Start the Vagrant Virtual Machine
- Clone this repo
- Go into the local repository from the step above
- run `vagrant up`
- Now wait for the process to complete

## Open the Virtual machine (debian 8)
- The default username and password is **vagrant**

## What's provided?
- IntelliJ Idea (CE)
- SUT (springmvc-shoppingcart-sample)
- API test (Rest-Assured)
- GUI web test (SeleniumBDD)
- Maven
- Java Development Kit (1.8)
- Firefox and Chrome
- Shortcut to start the Demo app and Idea should be present on the desktop (note that the desktop icons are hidden by default on Gnome)

## Support 
- In case of any questions or concerns regarding this VM please contact eric.de.graaf@alten.nl

