![Environs logo](https://raw.githubusercontent.com/GoogleDeveloperExperts/Environs/master/logo.png)
==========

For both hosts and participants, a lot of times doing an Android based code-lab or workshop feels like being given a box of screws and a hammer, and being told 'get to work'. One of the major problems is that getting the Android development environment set up initially is not trivial, and fairly error-prone. As a result, many times workshops end up being mostly about setting up development environments, and very little about actually building stuff. 

This project provides a VirtualBox image, along with instructions, that can be distributed on a flash drive, with everything set up and ready to go. 

### Instructions

1. Download the image from here: http://goo.gl/JYevDF
1. Verify the MD5 sum: 79fc818ac8d18fd1df9f68eec0513565
1. Extract the tbz2 archive
1. Copy contents to flash drives
1. Distribute flash drives
 
For participants:

1. Install 7zip software from flash drive
1. Extract the 7z Environs archive to computer (will not fit on flash drive)
1. Install VirtualBox 4.3.20 from flash drive
1. Import the .ova file into VirtualBox 4.3.20
1. Fire it up
1. Credentials are dev/dev (user/pass)

During the event, pass out a flash drive with the VirtualBox installers for every system, as well as Environs.ova. Have participants install VirtualBox and then import the Environs file. (They’ll need about 16GB free disk space.)

### Notes:

* You must be running on an x86_64 host.
* Must have ~30GB free disk space
* SDK and Studio are installed in ~/bin/
* Code lives in ~/workspace/
* Many Glass samples have been pulled down, and imported into AS
* There should be NO EMULATORS (obvious performance issues)
* Other things installed:
    * Emacs
    * Maven
    * Vim
    * Java 7
    * Android Studio 1.0.2

### Suggestion:

If you want to use this in your own workshop, pull it down, and try it out first. If you have a specific sample project(s) that you want to use, pull it down, import it, and test it out before putting this on a bunch of flash drives. 
