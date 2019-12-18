Projct name: The Globe
The Globe is a simple desk toy that provides local time using the "time" 
library of Python and has a small cool-looking globe spinning at a speed 
set by the user.
To use The Globe simply connect it to a power source and slide the switch
at the top ofthe box. This will turn on an LED light that will be picked 
up by a light sensor, subsequently turning on the clock and making the globe
spin. The angular velocity of the globe can be changed via a potentiometer
located in between the LCD clock display and the on-switch. If you have the
PocketBeagle hooked up to a computer and an IDE like Cloud9 open, you can see 
the servo duty being used and adjust the velocity based on that. Duty ranges 
from 15 to 80, making it coser to 80 will reduce velocity, while nearing it 
to 20 will increase velocity; once the duty cycle goes under 20, the globe
will begin spinning at full velocity in the opposite direction of how it usually
spins. If you only have the PocketBeagle connected to power rather than a computer,
you can still estimate how fast the globe will spin, simply remember that the
further left the potentiometer is turned, the faster the globe will spin, and
if it is turned all the way to the left, it will spin in the opposite direcion.

For a more detailed guide in how The Globe works and how it was built, check out
this Hackster.io page.

In this repository you will find everything needed to create a PCB of The Globe, enjoy.
