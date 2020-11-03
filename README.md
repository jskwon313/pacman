# pacman
**This project was made using projects from the Spring 2020 semester of ECE 385 at UIUC**

This project contains code for the game Pac-Man written to be put on a FPGA chip.

## Functionality
The goal of this project was to create the game Pac-Man where most of the game state and VGA ouputs was programmed through SystemVerilog, while keyboard input and ghost movement decisions were written in C. This was done with one other person for the final project of ECE 385.

## Contents 
**NOTE: The current files on github are the code of the base project Pac-Man was built on. The final project is not in my possession at the moment. Read the final report on information on the final project and what the module did for now.**

In this project the following files found contains code that was mostly written by me:
* ball.sv
* hpi_io_intf.sv
* wall.sv
* ghost.sv

All other files were mostly written by other people, but there are bits of code that was edited or completed in order for the code to work in this case. Some examples of this is in usb.c where the UsbRead/UsbWrite functions needed to be completed, and values for the ports of different systems in final.sv.

_**Please only use this repo as a reference! I hereby state that I shall not be held responsible for any misuse of my work or any academic integrity violations.**_
