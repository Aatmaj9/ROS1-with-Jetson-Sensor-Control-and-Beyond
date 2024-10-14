# ROS-with-Jetson-for-AUVs
We will be learning the basics of Jetson and how to integrate it with Arduino and various sensors like depth sensor, imu etc.
Here we will be working on Jetson Orin Nano with Jetpack 5.1.1 which has Ubuntu 20.04 based root system. The ROS version we will be using is ROS1 - Noetic.

**Setting up Jetson Nano**

Requirements :
Monitor , Micro usb to usb for powering on jetson , hdmi cable for viewing jetson on monitor , SD card , Ethernet cable ( Router if required)

Part 1 - 

Step1 : Insert SD card in your laptop and download the image for nvidia website. Flash the image on the SD card using a flashing tool ( rufus )

More clarification regarding the image - 

JetPack includes Jetson Linux with bootloader, Linux kernel, Ubuntu desktop environment, and a complete set of libraries for acceleration of GPU computing, multimedia, graphics, and computer vision. It also includes samples, documentation, and developer tools for both host computer and developer kit, and supports higher level SDKs such as DeepStream for streaming video analytics, Isaac for robotics, and Riva for conversational AI. 


For Jetson Orin nano we downloaded Jetpack 5.1.1( as we were using ros1 )
It includes Jetson Linux 35.4.1 BSP with Linux Kernel 5.10, an Ubuntu 20.04 based root file system, a UEFI based bootloader, and OP-TEE as Trusted Execution Environment.


Note : If you want to upgrade to ROS 2 later we have to install Jetpack 6 which includes Jetson linux 36.2 which packs kernel 5.15 and Ubuntu 22.04 based root system.


https://developer.nvidia.com/embedded/jetpack-sdk-60dp 

Here we will be working on Jetpack 5.1.1 with Ubuntu 20.04 and ROS Npo


Step2 :  Insert the SD card in jetson. Connect jetson to power source and ethernet for internet . Connect monitor and jetson using HDMI cable. Go through the initial setup on screen.
You can see Jetson OS on the monitor.



