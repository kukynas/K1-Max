# About this mod
It mainly fixes dimensional accuracy, belt path and improve input shaper resonances for both XY axis due to better support provided to the rods by new stepper/idler mounts and XY joints. One important fact, you'll lose about 5mm of your X travel but build area is bigger than the allowed print area so all should remain the same from print size perspective, you might need to update your printer.cfg if needed and shorten the X travel, make sure you watch your gantry for the first time as I couldn't test it on K1 (only K1 Max). Gantry is compatible with 16T-26T stepper pulleys so for stepper motors you either use your existing and just change the pulleys to 16T-26T or you'll need new steppers and new pulleys, maximum size of the pulleys allowed is 26T, you will also need to change your printer.cfg parameters, "rotation_distance:" according to your chosen pulley (i.e. 16T x 2mm = 32), sensorless homing "driver_SGTHRS:" for both X and Y, you need to experiment as there's no rule for the correct number, start with 100, if the toolhead doesn't move then go down in 5 increments (95, 90, etc.) if the toolhead is smashing against the frame you need to increase the number (105,110, etc), you might need to cut few teeth from your original belts, how much depends on pulleys chosen, make sure you won't cut too much so that your tensioners are released as much as possible to keep suficient amount of belt/pulley teeth contact for sufficient grip 

# Print setting for XY joints and additional assembly/sourcing info
Print with ASA, ABS, PA6/12, PET or any other high temp material, 35-40% infill, 0.16mm layer hight, 4 walls, 8 top/bottom layers, with support as per sliced sample attached 

![image](https://github.com/kukynas/K1-Max/assets/111185750/8ea78cc5-16e3-4fcc-9b98-e0a3b24c81c4)

Tolerances are really tigth to prevent potential wobble over time but trimming is not necessary, push/pull the rods in/out couple of times   

# BOM
XY joints:

- 8 x F623ZZ (3x10x4mm) flanged bearings

- 4 x M3x20mm grub screw

- 4 x 0.1-0.2mm M3 washer (between each stack of bearings)

- 2 x original LM8LUU bearings

- 2 x original M3 screws holding bearings in place


.

Stepper Mounts:

- 12 x F624-2RS (4x13x5mm) flanged bearings

- 6 x 0.1-0.2mm M4 washer (between each stack of bearings)

- 8 x 3x5x5 heat insert

- 8 x M3x6 FHCS screws

- 4 x 0.5mm M3 washer (under the tensioner release screws)

- all the other original parts (tensioners, tensioner idler pin, tensioning screws, stepper screws, original washer used between idlers)


.

Idler Mounts:

- 4 x F624-2RS (4x13x5mm) flanged bearings

- 2 x M4x20mm grub screw

- 2 x 0.1-0.2mm M4 washer (between each stack of bearings)

- 8 x 3x5x5 heat insert

- 8 x M3x6 FHCS screws


![image](https://github.com/kukynas/K1-Max/assets/111185750/5482d30a-b311-4728-830f-4570eb04767a)
![image](https://github.com/kukynas/K1-Max/assets/111185750/d6c2472f-de5c-41c7-afa3-5d19fb37f812)

.


Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)



