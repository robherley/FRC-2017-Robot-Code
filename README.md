# FRC-2017-Robot-Code

**Current Drive System:** 
* Tank Drive 
  * Left Motor [PWM 0]
    * Talon SRX
  * Right Motor [PWM 1]
    * Talon SRX

**Current Actuators:**
* Gear Gate [Solenoid 0]
  * Single Solenoid
* Climb Motor [PWM 0]
  * Talon SRX
* Shooter Motor [PWM 1]
  * Talon SRX


--
Robot currently has the following button mappings:
```
// Axis
Left Stick Y-Axis (Axis 1) - Left Tank Drive
Right Stick Y-Axis (Axis 5) - Right Tank Drive
LT (Axis 2) - Gear Gate
RT (Axis 3) - Shooter Motor

// Buttons
LB (Button 4) - Climb Motor
```
--
####Todo: 
Reconsider the button mappings for Gear Gate and Climb Motor, you currently have a button (boolean) to control a motor (which should be a float, to vary speed). Also, you currently have an axis (float) to control a solenoid that has binary states (On/Off). Maybe switching these two would be a better approach.

--
**How to use:** Place folder into "Labview Data" folder in Documents, open 2017 Robot Code.lvproj in Labview.

**How to upload to robot:** Click Build Specifications. Right click "FRC Robot Boot up Deployment. Click "Build" first, then "Run as startup"

--