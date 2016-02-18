# hextimwall
![Alt text](http://i.imgur.com/KVkHlYF.png "Optional title")
# Introduction
This is a project I worked on in July 2014 that changes the wallpaper of a Windows computer based on the time of day.  I chose the name hextimwall because this program uses hexadecimal color values and the current time to change the computer wallpaper.  I used Java, Eclipse IDE, bat scripting, and PowerShell.  The code was lost after switching from my Windows desktop computer to my MacBook.

# Basic Overview
The program converts the current time (HH:mm:ss) to HHmmss and adds a # to the beginning so that it looks like so:
\#HHmmss

The program then paints a 1920x1080 image with that specific color code and sets it as the background of the computer.
