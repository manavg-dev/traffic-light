
# traffic-light
## Overview
This circut simulates a traffic intersection with a pedestrian crosswalk using an Arduino.
The system controls traffic lights and allows pedestrians to cross using a button input.

## Components
- Arduino Uno (1)
- LEDs (Red, Yellow, Green)
- Push button (1)
- 1KΩ Resistors (4)
- 220Ω Resistor (1)
- Breadboard (1)
- Jumper wires (Multiple) 
- Potentiometer (1)
- LCD (16 x 2) (1)

## Skills learned
- Programming using C++
- How to use a LCD

## How it works
1. The system begins with the traffic light set to RED.
2. After the programmed delay, the traffic light changes to GREEN, allowing vehicles to proceed.
3. The light then changes to YELLOW to warn that it is about to stop traffic.
4. If the pedestrian button has been pressed, the system will activate the pedestrian crossing sequence.
5. The LCD display provides information about the current traffic state.
6. Once pedestrians have crossed safely, the system returns to its normal traffic light cycle.

## Circuit Images
### Green Light, Cross
![Green Cross](images/green-cross.png)

### Green Light, Don't Cross
<img src="images/green-dont-cross.png" width="400" height="300">




