# Project Name 
<h3>Wheatstone Bridge Smoke Detector</h3>

# Project Description 
Wheatstone bridge is a popular network configuration for detecting small changes in quantity.

<p align="center"><img src="Images/Wheatstone%20Bridge.PNG" alt="Alt text" width="600" height="500"></p>

<div align="center"> <b>Figure 1:</b> Wheatstone bridge smoke detector: (a) DC bridge configuration; (b) outside appearance; (c) internal construction </div><br>

<h3>Working Principle:</h3> <i>In Figure 1(a)</i>, the DC bridge configuration uses a photoelectric device to detect the presence of smoke and to sound the alarm. A photograph of a photoelectric smoke detector appears in <i>Figure 1(b)</i>, and the internal construction of the units is shown in <i>Figure 1(c)</i>. First, air vents permit the smoke to enter the chamber below the clear plastic. The clear plastic prevents the smoke from entering the upper chamber. Still, it permits the light from the bulb in the upper chamber to bounce off the lower reflector to the semiconductor light sensor (a cadmium photocell) at the left side of the chamber. The clear plastic separation ensures that the light hitting the light sensor in the upper chamber is not affected by the entering smoke. It establishes a reference level to compare against the chamber with the entering smoke. If no smoke is present, the difference in response between the sensor cells will be registered as usual. Of course, if both cells were precisely identical and the clear plastic did not cut down on the light, both sensors would establish the same reference level, and their difference would be zero. However, this is seldom the case, so a reference difference is recognized as a sign that smoke is absent. However, once smoke is present, there will be a sharp difference in the sensor reaction from the norm, and the alarms should sound.

<i>In Figure 1(a)</i>, we find that the two sensors are located on opposite arms of the bridge. With no smoke present, the balance-adjust rheostat ensures that the voltage V between points a and b is zero volts and the resulting current through the primary of the sensitive relay is zero amperes. Looking at the relay, we find that the absence of a voltage from a to b leaves the relay coil unenergized and the switch in the N/O position (recall that the relay switch position is always drawn in the unenergized state). An unbalanced situation results in a voltage across the coil and activation of the relay, and the switch moves to the N/C position to complete the alarm circuit and activate the alarm. Relays with two contacts and one movable arm are called single-pole–double-throw (SPDT) relays. The DC power is required to set up the balanced situation, energize the parallel bulb so we know that the system is on, and provide the voltage from a to b if an unbalanced situation should develop.

Why do you suppose that only one sensor isn’t used since its resistance would be sensitive to the presence of smoke? The answer is that the smoke detector may generate a false readout if the light intensity of the bulb's supply voltage output varies. Smoke detectors of the type just described must be used in gas stations, kitchens, dentist offices, and so on, where the range of gas fumes present may set off an ionizing-type smoke detector.

# Materials to Use 
Please use a battery for the DC supply. You can use LDRs (Light Dependent Resistors) for the sensors. You can construct the smoke detector assembly using opaque paper, cardboard, or similar material.
