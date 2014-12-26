![Environs logo](https://raw.githubusercontent.com/GoogleDeveloperExperts/Environs/master/logo.png)
==========

For both hosts and participants, a lot of times doing an Android based code-lab or workshop feels like being given a box of screws and a hammer, and being told 'get to work'. One of the major problems is that getting the Android development environment set up initially is not trivial, and fairly error-prone. As a result, many times workshops end up being mostly about setting up development environments, and very little about actually building stuff. 

This project provides a VirtualBox image, along with instructions, that can be distributed on a flash drive, with everything set up and ready to go. 

### Instructions

* Download the image from here: http://goo.gl/W6OQA7
* Verify the MD5 sum: 935f80992c6d4ec638382f9626a2fe7a
* Import the .ova file into VirtualBox 4.3
* Fire it up
* Credentials are dev/dev (user/pass)

During the event, pass out a flash drive with the VirtualBox installers for every system, as well as Environs.ova. Have participants install VirtualBox and then import the Environs file. (They’ll need about 16GB free disk space.)

### Notes:

* You must be running on an x86_64 host.
* Must have 16GB free disk space
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
