# LABVIEW-Keyboard-XY-Stage
Control with Labview of a Physik Instrumente (PI) XY stage + Physik Instrumente (PI) Z-piezo stage + a Nikon TI2 microscope


## Aim
This software is designed to control a PI C867 + E709 and a Nikon TI2 microscope with the keyboard.

## Prerequisites

<ul>
<li> You need to install the latest version of the PI software suite</li>
<li> You need Labview 2023 32-bit or a newer version</li>
</ul>

## Installing
Copy and paste to your local drive all the files contained in the "Labview_codes" folder.

## Running the tests


![image](https://github.com/MAILFERT-Sebastien/LABVIEW-Keyboard-XY-Stage-NikonTI2/blob/main/Images/GUI.PNG) 

<ul>
<li> Double-click on the <i>Keyboard_Main.vi</i> file</li>
<li> Click on the Run arrow to run the vi</li>
<li> Two panels are available:
	<ul>
		<li> <i>User panel</i> tab:</li>
		<ul>
		<li> <i>Dia lamp</i>: open/close the dia lamp shutter (also get its status from the microscope)</li>
		<li> <i>Dia lamp intensity</i>: set the dia lamp intensity  (also get its status from the microscope)</li>
		<li> <i>Objective</i>: select the objective (also get its status from the microscope)</li>
		<li> <i>Light path</i>: select the output port  (also get its status from the microscope)</li>
		<li> <i>Z pos</i>: set the Z-piezo position of the objective turret (also get its status from the microscope)</li>
		</ul>
		<li> <i>Status panel</i> tab</li>
		<ul>
		<li> <i>Nikon cluster</i>: current status of the microscope</li>
		<li> <i>C-867 cluster</i>: current status of the XY stage</li>
		<li> <i>E-709 cluster</i>: current status of the Z-piezo stage</li>
		<li> <i>Relative Z obj move (au)</i>: set the step of the Z objective movement</li>
		<li> <i>Relative XY move (mm)</i>: set the step of the XY stage movement</li>
		<li> <i>Relative Z move (µm)</i>: set the step of the Z-piezo movement</li>
		</ul>
	</ul></li>
<li> Commands to move the XY stage, the Z-piezo stage or the objective
	<ul>
		<li> <i>Shift + Right arrow</i>: move the X axis one step forward</li>
		<li> <i>Shift + Ctrl + Right arrow</i>: move the X axis forward several steps</li>
		<li> <i>Shift + Left arrow</i>: move the X axis one step backward</li>
		<li> <i>Shift + Ctrl + Left arrow</i>: move the X axis backward several steps</li>
		<li> <i>Shift + Up arrow</i>: move the Y axis one step forward</li>
		<li> <i>Shift + Ctrl + Up arrow</i>: move the Y axis forward several steps</li>
		<li> <i>Shift + Down arrow</i>: move the Y axis one step backward</li>
		<li> <i>Shift + Ctrl + Down arrow</i>: move the Y axis backward several steps</li>
		<li> <i>Shift + PageUp arrow</i>: move the Z axis one step forward</li>
		<li> <i>Shift + Ctrl + PageUp arrow</i>: move the Z axis forward several steps</li>
		<li> <i>Shift + PageDown arrow</i>: move the Z axis one step backward</li>
		<li> <i>Shift + Ctrl + PageDown arrow</i>: move the Z axis backward several steps</li>
		<li> <i>Shift + 8 arrow</i>: move the Z-objective axis one step forward</li>
		<li> <i>Shift + Ctrl + 8 arrow</i>: move the Z-objective axis forward several steps</li>
		<li> <i>Shift + 4 arrow</i>: move the Z-objective axis one step backward</li>
		<li> <i>Shift + Ctrl + 4 arrow</i>: move the Z-objective axis backward several steps</li>
	</ul></li>
</ul>





## Versioning

<ul>
<li> V1.0, 240214</li>
</ul>


## Authors
Sébastien MAILFERT
Institut Fresnel (Marseille, France), CNRS, AMU

## Licence
GNU General Public License v3.0
GNU GPLv3.0

## Acknowledgments
Sébastien MAILFERT
