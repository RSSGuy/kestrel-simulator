## kestrel-simulator 

###What it is
The Kestrel simulator is a browser cockpit console for the KF-07 Kestrel mobile suit. It’s the capstone of the Designer Learning Path: a small but complete app, built by a designer by following the path’s tutorials, to prove they teach enough to ship real software.

###Who uses it
A pilot on a single mission: fly out, retrieve an antimatter sample, and bring it home. One sitting is one mission, about five minutes.

###What’s on the console (subsystems)

Reactor: power output and how much each subsystem is drawing
Sensors: online or offline, and the result of the last scan
Thrusters: burn mode (idle, cruise, full)
Containment: empty, holding the sample, or failing

Each subsystem shows a status of nominal, warning or offline.

###What the pilot can do (orders)

Approach: thrusters go to cruise, power draw rises
Scan: sensors report whether the sample is in range
Capture: containment changes from empty to holding
Hold: thrusters go to idle, containment stays powered
Dock: mission ends, the console shows a mission summary

Every order is recorded in a mission log on screen, with the time and the result.

###Out of scope for version 1
Combat, multiple pilots, and any 3D view.

Status
In progress. Built step by step along the Designer Learning Path.