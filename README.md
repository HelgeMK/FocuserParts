# FocuserParts

In this repository I am maintaining files and other information that describe how the focuser has been built.

For designing and 3d printing of the gear-wheels I have been using this configurator, which directly provides the files that can be opened in Cura. I have been printing the parts with an Anycubic (MEGA) printer and PLA filament.

To prevent the belt slipping off the gearwheel, I have downloaded the igus-file in format STEP and uploaded in FreeCAD, in order to attach to the left and right of the gearwheel a "disk". See uploaded file, named gearwheel_8mm.

The belt is a T2.5 145mm (6mm width).

https://www.igus-cad.com/default.aspx?treeid=10300389991&cul=en-gb&_ga=2.160246462.2040466429.1546352162-1216108876.1539955177

As a controller I am using a Pololu T825 stepper controller. See TicFocuser repository for guidance on the software.

