# Balance channels
This feature allows you to balance selected pairs or a group of up to 4 channels to ensure that they move in unison. For example, unbalanced flaps can result in unwanted roll, while unbalanced throttles on multi-engine models can result in unwanted yaw.

## Overview
This feature automatically creates a differential balance curve for each channel selected. The number of balance points may be chosen. By comparing the physical positions of control surfaces (such as flaps) at each point of the curves, they can be easily adjusted to be equal. The final result is perfectly tracking surfaces.

## Prerequisites 
Prior to balancing channels, this recommended process should be followed:

## Configuration 
- When activated, the channels to be balanced are chosen, as well as the number of balance curve points, and whether to smooth the curves. The channels will be displayed in the order of selection. The mix outputs are shown along the X axes, while the balance adjustment differential values are shown on the Y axes.
- [Joystick icon] Input options: The source(s) configured in the channel mixes may be used, or optionally any other convenient analog input. If you select this 'Auto analog input'option, the first stick, slider or pot you move will be used as the source for X, not only in the graph, but also in the model.
- [Magnet icon] When selected, the nearest curve point on the X axis will be automatically selected for adjustment with the rotary encoder. When deselected, the curve point to be adjusted can be selected using the 'SYS' and 'DISP' keys. The input must be adjusted to align the X value with a curve point before adjustment is made.
- [Lock icon] Pressing the ENTER key will toggle Lock mode on and off. When enabled, all inputs are locked so that you can release the stick input, allowing you to observe the control surfaces while you adjust your curve.
- [Gear icon] takes you back to the configuration dialog.
- [?] This help file.