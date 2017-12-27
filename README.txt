Name: David Tu
Contact: david.tu2@csu.fullerton.edu / 626-497-3531

Please refer to the pdf file for source code listing as well as output results

Program Description: Solar System Simulation: This program demonstrates our Solar System
It also includes rings for Jupiter, Saturn, Uranus and Neptune and shows the orbit of the Earth and Moon
Please note that the planets are larger than they should be but can be reverted back to their actual sizes by setting "EarthMoonView = True"
When to scale, you should also be able to view the Moon orbiting around the Earth by zooming in

How to Run the Program:
	Pre-Requisite(s): Installation of VPython

	1. Open VIDLE, the IDE that comes with the installation of VPython
	2. Once you are in VIDLE, go to File > Open...
	3. While in the Open window, search for Solar System.py, then click Open
	4. You should now be able to view the source code for Solar System.py. To run the program, go to Run > Run Module
	5. By default, you should be able to view the entire Solar System, scaled up (due to the planet sizes being too small to view)
		To view the actual unscaled sizes and to be able to view the Moon orbiting around Earth without any scaled obstruction, you need to modify one line of code:
		Change "EarthMoonView = False" to "EarthMoonView = True", then repeat step 4
		You should now be able to view our unscaled Solar System. If you zoom in while in this mode, you can observe the Moon orbiting around the Earth 

Known Bugs/Issues: There was an issue with the planets being too small to view. To make them viewable, I had to scale them up. However, when scaling up the Solar System, the Earth's Moon was obstructed by the size of the Earth
The current workaround for this is by controlling the scale with the variable, "EarthMoonView"
When this variable is set to False, you should be able to see the planets and the Sun due to the scaling but will be unable to view the Moon (It will look like the Earth "ate" the Moon)
When this variable is set to True, you will view the unscaled Solar System. However, if you zoom in on the Earth when in this mode, you should be able to view the Moon orbiting around the Earth
The reason for doing this is because I didn't want to change the distances of the scaled planets in order to view the Moon, as that would be inaccurate to NASA's planetary data