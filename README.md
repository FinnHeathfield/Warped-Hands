# Warped-Hands
An interactive sound exibit using hand tracking to controll a granular synth.

This project uses the Node for Max hand tracking project from [Lysdexic-audio](https://github.com/lysdexic-audio/n4m-handpose).

## Required Dependancies
This patch required the [Flucoma](https://learn.flucoma.org/) package which is avaliable from the Max package manager.

## Installation
The two main folders should be downloaded and the folder path of the cellosamples folder should be pasted into a message box leading to the conformpath object.

## Presenting the work
When presenting this work in a performance setting, I ran into a number of problems trying to keep the webcam active when using the patch without seeing the atom app window the n4m-handpose runs in. As a workaround, the sysem should be started, then the window should be captured using OBS. By using the virtual webcam function in OBS, the cropped video can be streamed to Max in the jit.grab object. I then set my background to black, system to dark mode, and hid the dock and top menu bar (only for mac users). I also entered presentation mode and hid the menu bars in Max.


