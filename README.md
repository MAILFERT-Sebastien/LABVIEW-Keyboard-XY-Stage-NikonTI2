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
<ul>
<li> Double-click on the <i>Keyboard_Main.vi</i> file</li>
<li> Click on the Run arrow to run the vi</li>
</ul>

![image](https://github.com/MAILFERT-Sebastien/LABVIEW-Keyboard-XY-Stage-NikonTI2/blob/main/Images/GUI.PNG) 

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
