# Unix-Final-Project
Contributors: Dinal Patel, Emmy Ea

## 1. Project description/goals:
For our project we chose to do a purpose-specific desktop system using Debian as
our base OS. Our goal is to create an Operating System specifically for music
production. Our aim is for users to navigate through their favourite music applications
with ease. We will provide Audacity and VST Plugins since they are free. The user
will also be able to download more softwares of their choice if they need depending if
the packages are available.

## 2. Platform of choice:
Our platform of choice is the Oracle VM VirtualBox using Debian. We chose to use a
VM because we do not have a Linux OS installed, and we have been using
VirtualMachine throughout the semester. This project will be available and updated
using GitHub to keep track of our process and mistakes.

## 3. Requirements:

• The creation of multiple user accounts: Users can be created within the terminal
and assigned a unique password to each, using root.

• Process or service management: We will record our process and failures to adapt
to them. We will provide steps for the installation of our OS, including
the passwords.

• Basic system security: Upon login, users will need a password to access our OS.
As sysadmins, we will grant all access only to the main user and read/execute only
to the other users.

## 4. Major technical solutions compared:
Solution 1: Debian, because we’ve both used Debian as our primary OS for all our
labs and we are more familiar with it. Also supported by the school computers.
Solution 2: Fedora.

## 5. Timeline:
Week 1: Brainstorming and writing the proposal. Getting a general idea of how to
implement our ideas in the VM. 
Week 2: Start structuring the base of our project and planning steps. Working on the
requirements and solution.
Week 3: Recap what we’ve accomplished so far and what is left to meet the
requirements. Try to complete the core of the project. Have the completed guide to
installation. Make sure applications are pre installed.
Week 4: Final touches and presentation.

## USER INFO:
This desktop is for anyone who loves to make music and loves to listen to music. This 
desktop is catered to a younger audience, anyone from 12-35, but any user can enjoy it.
Using Debian will make it easier for new linux users to navigate through this desktop. 

Charlie is a 22 year old who aspires to produce music for her band. Her friends do not
know how to make music so he tries find a simple beginner friendly music production 
desktop provided with apps. The problem is that he cannot find any that is beginner
friendly and found the applications overwhelming for new music lovers. That why we made 
this new desktop, for people who are learning/beginners to music prodiction. 

## Customization of desktop
Cinnamon allows users to customize the icons of each shorcuts by right clicking and selecting properties. And clicking on the icon image. 
You can also change the size of your icons by right clicking your desktop and selecting customize. Unselecting auto-arrange allows users to freely place their shortcuts.

## Installation guide for packages (sysadmins)
• sudo apt-get upgrade, to insure that you have the latest versions of the packages available. 

• https://blends.debian.org/edu/tasks/music, offers users a list of available in Debian 11 on installation. It does not require additional download. 
example: sudo apt-get install audacity, will install audacity to your VM. All users will have access to those applications without needing to redownload them through their own terminal. 

• To add shorcuts to the desktop, simply search for the application name and right click and select add to desktop. 
• To add shorcuts to the desktop using launchers, right click your desktop. Select "Create a new launcher here". Enter and name. Browse in command, select other location. Pick computer. Select lib folder. For example find the firefox-esr folder and select firefox-esr. This should allow you to add a launcher.




