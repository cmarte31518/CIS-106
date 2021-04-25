  *Crismely Marte CIS 160*

## Lecture 2 Installing Ubuntu, Virtualization, and the Raspberry PI ##
-----------------------------------------------------------------------

### The Basics of Virtualization 
* Virtualization is defined as a replica of hardware to simulate a virtual machine inside another computer. ( **A computer inside another computer**)
  
    * **2 Types**
![ImageHy](../Notes%20lec%202/HyperType1n2.png)
        1. Server-Side Virtualization 
             Takes places on a server 
            - Example: Virtual Desktop Infrastructure (VDI) Thick Client, Thin and Zero client. 
        2. Client-Side Virtualization
            - Takes place on a client (local computer)
            - The computer running the virtualization is called **Host Comp** 
            - The virtual computer is called **Guest Comp**
            - #### Requirements  
               - Hypervisor 
               - Capable CPU minimum Dual-Core
               - RAM >= 2GB
               - Enough Storage
               - Video Graphics 128MB

#### Hypervisor

  * **2 Types** 
    1. Type 1: Runs on the computer as the actual OS by replacing the existing OS
    2. Type 2: Runs on the computer as an Application such as Virtual Box it requires your machine to run a OS before installing

#### Advantages of Virtualization
- Allows the user to test app
- Allows the user to run multiple OS
- It is less in cost
- Decreases risks by allowing user to experiment without worrying about viruses.
  
### Using Virtual Box
![VB](../Notes%20lec%202/VirtualBoxlogo.png)
* VirtualBox is one of the most used type 2 Hypervisors 
  - Very popular because it run on a large range of Operating Systems
  - Could be easily installed by simply searching **VirtualBox Download** and downloading the correct extensions to enhance the performance

**VirtualBox Settings**

These images explain most of the basic VirtualBox settings
![ImageVB](../Notes%20lec%202/VBSetting.png)

### Installing Ubuntu Virtual Machine
- First you need to search Ubuntu.com and download 
- Go to the the VM settings and go to storage and once your ubuntu package is downloaded go to Optical Drive and open the Package to automatically have ubuntu added.
- The once you open VirtualBox click on new to machine then name it.
- Choose your memory size 2GB, Create hard disk then use click dynamically allocated then for the file location and size it should be 50GB.
- Then in the settings you should customize your virtual machine then once your done the machine should be ready to start. 
- This process takes some time which is important to be detailed with all the thing your machine needs

### Installing Ubuntu On Raspberry Pi
***This is the process that i went through because I have a Raspberry Pi***
- First, before setting everything up, take the Micro SD along with the adapter and connect it to your computer
- Then download Raspberry Pi Imager
- Then you need to go to Ubuntu.com and click Raspberry PI and click Get Ubuntu for Raspberry Pi
-Then open Raspberry Pi Imager,  choose Ubuntu as the OS and then choose your memory card and press write 
- Then assure that you physically set up your Raspberry Pi and once you run it choose Ubuntu as the OS and it would take you to the OS every time you turn on your Raspberry Pi 

### What is a Raspberry Pi
- In my own words a Raspberry Pi is a mini computer that can be carried in your pocket plus all the other cables that it comes with but, it is functions good and most importantly it is cheap.

#### What it is composed of
![imageRp](../Notes%20lec%202/Rasppi4.png)

#### The main components you need to have a working Raspberry Pi
![Image](../Notes%20lec%202/Raspcomp.png)


