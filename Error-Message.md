# Error Messages

## “Working pallet disappear cause pause” 
Situation: The pallet sensor did not detect the working pallet normally. 
Reset Procedure: Make sure the sensor detect the working pallet normally, then press “Start” to continue.

## “Layer Protection! Please remove Right/Left side pallet box cause PAUSE”
Situation: The project paused to prevent robot from hitting the opposite working pallet boxes. 
Reset Procedure: Clear the full state of the pallet and press “Start” to continue.

## “No box detected on gripper, cause PAUSE”
Situation: Robot detects abnormal air pressure on the tool when grapping the box. 
Reset Procedure: Check box drop situation and stop the project. Then restart the project when it is ready. 

## “Air source pressure too low! cause PAUSE”
Situation: Air pressure is abnormal. 
Reset Procedure: Check incoming air pressure value. Then, press “Start” to continue.

## “Grab fail cause pause! Resume after checking”
Situation: The robot failed to grab box on the conveyor 
Reset Procedure: Check sensor signal on the conveyor. Then, press “Start” to continue.

## “Project initial with box on tool, cause pause”
Situation: Project starts with box on robot tool. User has to remove the box on gripper. 
Reset Procedure:  
- Press “Stop” to stop the project. 
- Remove the box from the gripper. 
- Place the box in the picking position. 
- Press “Start” to start the project again.
