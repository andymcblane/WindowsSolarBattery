# WindowsSolarBattery
Report to Windows the status of an external battery system - typically when a computer is running off of a solar system 

Originally I wanted to create a custom Windows battery driver so it would interface nicely. 

Now I will be creating a custom app in Java with similar behaviour (% charge, time left of battery at current load levels.)

The hardware will be pretty simple, just a voltage divider to read the voltage with an arduino, and a current shunt (with an op-amp). 

This will be transferred over serial over USB (bluetooth setup could be used for a laptop), into a Java application which will draw graphics to the screen in the system tray. Will look into making the code Windows and Linux / MacOS friendly. Will hopefully have some kind of cli interface. 
