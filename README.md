# hex-wall

![demo image](http://i.imgur.com/KVkHlYF.png "hexwall demo image")

# Introduction
This is a project I worked on in July 2014 that changes the wallpaper of a Windows computer based on the time of day. I chose the name hex-wall because this program uses hexadecimal color values and the current time to change the computer wallpaper. I used Java, batch scripting, and PowerShell.

# Overview
The program converts the current time (HH:mm:ss) to HHmmss and adds a # to the beginning so that it looks like so:
\#HHmmss

The program then paints a 1920x1080 image with that specific color code and sets it as the background of the computer.
