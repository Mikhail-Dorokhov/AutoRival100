# AutoRival100

This is a WIP project to automate the built in lights on my mouse, a Steelseries Rival 100. I started this project to gain more experience with interacting with devices by writing information to the virtual HIDRAW files used by Linux and to gain some experience with developing automated code as practive for future projects. 

##Current State

So far, I have modified some example code from [Signal11](http://www.signal11.us/oss/udev/) to consistently and accurately find which HIDRAW file the mouse is curently associated with as this is subject to change. I also already know what information I need to write out to the file to set the color of the lights.

##Plan
 I am currently working on cleaning up the code to turn it into a usable functional that can find the HIDRAW interface for any USB device if given the devices Manufacturer and Device ID numbers. Next, I need to calculate sunrise and sunset times in C as well as develop a script that takes in the filepath of the HIDRAW file and a hex representation of the color the mouse should be set to.
