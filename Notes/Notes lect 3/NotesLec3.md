*Crismely Marte CIS 160*

## Lecture 3 Desktop Environments, Shell, Managing Software, The linux Filesystem
---------------------------------------------------------------------------------
###Desktop Environment
- I basically a bunch of software running on an OS that makes up the GUI.
  - **GUI**
    - Graphical User interface 

**Some of the Linux Graphical Desktops**
![Image1](../Notes%20lect%203/DeskEn1.png)

**Gnome DE**
- Linux Default Desktop (Gnome 3)
- DE that is mainly made up of free and open source software
- Started in 1997 by Miguel de Icaza
- User friendly 
- Has a lot of features to make the Desktop performance and to enhance it looks

**KDE (Kool Desktop Environment)**

###Shell

**History of the Bash Shell**
- In 1969 the development of different soon to be shells begin
- Mashey Shell and Bourne Shell where the ones that the community used the most
- The free software movement shell was written by Bryan Fox
- Fox finished the shell which completed the OS for the GNU project in 1989
- Bash has become part of almost every computer in the world.

**GNOME Terminal ShortCut Commands**

![Image2](../Notes%20lect%203/gnushortcuts.png)

**Basic & Useful Commands**

![Image3](../Notes%20lect%203/basiccommand.png)

##Managing Software

**Terminology**

  - Package: Like an archive contains all the things needed to install a program
    - Library
    - Dependency
    - Repository

**Wrapper Tool**
- Makes the management of certain apps easier

**APT Package Tool**
- Makes it simple for the user to install packages
- Installs the dependencies of the app you want to install
- Allows to resume installations
- Search for packages using Local cache 
- Use for updating all packages in the system

**Installing and Updating software**
![Image4](../Notes%20lect%203/installingsoft.png)
![Image5](../Notes%20lect%203/updating.png)
- To install just use SUDO + apt + install + package name
- To remove Sudo + apt + remove + package name
![Image6](../Notes%20lect%203/sudoexample.png)
![Image7](../Notes%20lect%203/sudoexamples2.png)

##The FileSystem
![image8](../Notes%20lect%203/filesystem1.png)
![image9](../Notes%20lect%203/root.png)

**Commands to organize files** 
- pdw: displays current directory
- cd: change directory using either Absolute or Relative Path
  - cd + destination
- ls: Displays whats inside your current directory (Long List)
1. **Absolute Path** always states the entire pathname including the root and the entire pathname to locate a certain file.
2. **Relative Path** shows the pathname to locate a file but that pathname starts from the current working directory
![Image10](../Notes%20lect%203/commads.png)

![Image11](../Notes%20lect%203/filepermission.png)