# FS19-TARGET-SCRIPT-Profiles
TThrustmaster TARGET profiles for usage in Farming Simulator 19. Initial keymaps based on FDR's Logging maps from https://www.fdrlogging.com/. Will be used to bring more advanced controls to T16000.m dual sticks in FS19.

----------------------------------------------------------

Zeplin SCRIPT Branch: https://github.com/zeplintwo/FS19-TARGET-Profiles/tree/Zeplin-SCRIPT

FS19-TARGET-GUI-One-Stick-Motion: https://github.com/zeplintwo/FS19-TARGET-GUI-One-Stick-Motion

FS19-FDR-TARGET-GUI: https://github.com/zeplintwo/FS19-FDR-TARGET-GUI

Zeplin SCRIPT Branch will have as much advanced TARGET scripting as I see fit. And will not hesitate to incorporate 3rd part/external sources if said sources are willing to allow usage of said scripts. Will not be compatible to Master branch. Parts may be compatible with FDR branch.

FS19-TARGET-GUI-One-Stick-Motion branch for Thrustmaster TARGET GUI profile updates and distribution. This will be the most basic of scripting and very little in the way of extra functionality. Will not be compatible with SCRIPT branch. May not be compatible with FDR Branch

FS19-FDR-TARGET-GUI Branch for Thrustmaster TARGET GUI is the direct layout a best as I can build that follows FDR’s key binding. This may have higher scripting functions in the future based off functions form the ‘Zeplin SCRIPT’ Branch. May or may not be compatible to Master or SCRIPT Branches

----------------------------------------------------------

Thrustmaster US website: http://www.thrustmaster.com/en_US
Thrustmaster US support: http://www.thrustmaster.com/en_US/support
Thrustmaster US T.16000m downloads https://support.thrustmaster.com/en/product/t-16000m-fcs-space-sim-duo-en/

Target software found in download link above under software as of this writing on March 12, 2020 the file name was T.A.R.G.E.T.-Software v3.0.18.328 v2. There is no direct link I can give. The version number will change in the future. 

----------------------------------------------------------

Installation:

1.	Download and extract the latest ‘source’ files. From https://github.com/zeplintwo/FS19-TARGET-SCRIPT-Profiles/releases
2.	Unpack zip and keep all files in same directory. 
3.	Open ‘TARGET Script Editor’ Open and Compile ‘FS19-Zeplin-FDR-Movment-v#.#.#.tmc
4.	Edit FS19-Zeplin-Settings-v#.#.#.ttm save changes if any
5.	Close ‘TARGET Script Editor’ window 
6.	Launch ‘TARGET GUI’ and ‘Run Configuration’ on FS19-Zeplin-FDR-Movment-v#.#.#.tmc. 
a.	You can also run the configuration from the Script Editor.
7.	Bind the recommended Joystick Axis in FS19 in the Options > Gamepad Controls
8.	Launch save game and enjoy. 

----------------------------------------------------------

File Usages:
FS19-Forestry-Motion-Layout.jpg
Forestry mode joystick graphic that show the button layout and what the assigned buttons do. As well as what is open for assignment
FS19-Tractor-Motion-Layout.jpg
Tractor mode joystick graphic that show the button layout and what the assigned buttons do. As well as what is open for assignment
FS19-Zeplin-FDR-Movement-v#.#.#.tmc
Main control script for the Dual T16000.M joysticks that has two motion control systems. One based on FDR’s Forestry keybinds. Second is based on tractor needs. Both are accessible at anytime via button press ingame
FS19-Zeplin-Keymaps-v#.#.#.ttm
Main keymap defines some are to make the scripting work properly some are stock FS19 keybinds. Only change the stock and scripting binds if you are using a non-standard key setup. All keybinds are in Thrustmaster ‘USB’ code to be valid over a larger number of keyboard layouts. Any changes in this files keybinds should use the ‘USB’ keys instead of direct character mapping.
FS19-Zeplin-Macros-v#.#.#.ttm
Macro and function scripting area. This is where the magic happens baby. Most things are commented for helping understand it use
FS19-Zeplin-Settings-v#.#.#.ttm
Settings are the intended area for the user to change the exposed setting for the script. There will be place holder setting for WIP functions.
LICENSE
Non-script related file. It is the usage and distribution license for the script project
README.md
This file that is displayed on GITHUB or as a first read to help with the use of the script
target_zeplin_dx128-v0.1.tmh
Modified version of the ‘target.tmh’ that renames the combined device and preps for 120 DX devices and 8 HAT Functions

----------------------------------------------------------
