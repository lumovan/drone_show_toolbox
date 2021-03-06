Drone Show Animation Toolbox for Blender 2.7x
---------------------------------------------
Martins Upitis (martinsh)

Kristaps Brass (kkbrass) - Proximity, Velocity checks and Export operators

Installation
------------

- download as a zip
- in Blender open User Preferences (Ctrl+Alt+U)
- under Add-ons tab, press "Install Add-on from file..."
- choose the downloaded .zip
- check the checkbox to enable it and "Save User Settings" to make sure it stays enabled
- Drone Show Animation Toolbox will appear in Blender Tool Shelf

Statistics
----------

- show length in minutes
- number of UAVs
- autopilot target framerate
- waypoint count to store in drone
- Blender framerate
- nth frame from Blender to be stored in drone

to do:

- calculate show bounding box

Visualisation
-------------

- drone names
- drone material color (LED)

to do:

- drone proximity area
- draw drones with OpenGL not mesh + material (?)
- path splines in 3D viewport
- visualize proximity and velocity warnings differently (listing every frame in output is difficult to read)

Checks
------

- Proximity based on minimum distance
- Velocity based on maximum velocity


Utilities
---------

- Add drone grid with automatic naming and material assign
- Remove drones
- Export

to do:

- add seperate drone grids for animation and coloring
- drone animation tools
- drone LED coloring tools
- edit drone paths with splines

Exporter
---------

- simple UI with format select (one format for now) and output path.