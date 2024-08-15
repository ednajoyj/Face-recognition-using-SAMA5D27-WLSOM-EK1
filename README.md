# Face-recognition-using-SAMA5D27-WLSOM-EK1
This projet is about doing AI Faial recognition using SAMA5D27 WLSOM-EK1 board. This board is ideal for evaluating and prototyping. It is the board used for industrial purpose. This page will guide you to use the board without facing any major issues. 

## Components needed
<ul>
<li>SAMA5D27 WLSOM-EK1 Board</li>
<li>SD Card</li>
<li>Card Reader</li>
<li>USB Camera</li>
<li>TTL to USB connector</li>
<li>Jumper wires</li>
<li>Power cable</li>
</ul>

## Booting
The OS that we use is Yocto project or Buildroot. The step-by-step guidance is as follows:
<ul>
<li>Install Balena Etcher software</li>
<li>install Yocto Project OS manually</li>
<li>Insert the SD Card reader with the SD Card to the laptop</li>
<li>Open Balena Etcher software and select 'Flash from file option'</li>
<li>Select the Yocto project file that you have dowloaded</li>
<li>Next, select the target USB Port</li>
<li>The file will start to flash automatically</li>
<li>After flashing open a software called Putty</li>
<li>Now connect the board to the laptop through TTL-USB converter, and connnect the power cable to the board</li>
<li>Insert the booted SD Card to the board</li>
<li>set up the putty and click open</li>
<li>A terminal will open, press start button and then the reset button on the board</li>
<li>Your board will start booting</li>
</ul>
Many a times you will face a lot of issues in booting your OS. And moreover you will not havean Os like the windows, instead you will have to work only with a terminal that is supported with putty software.You are supposed to finish all your work with only the terminal.


You will also face a lot of issues where you get a kernal panic error and your kernel gets killed automatically. When you face such issues clear all the files, format it from the begining and install the yoct Project from the first. If you still face the same issue try installing Buildroot OS, it is more comfortable to use buidroot than using Yocto Project.

## Setting up Putty
