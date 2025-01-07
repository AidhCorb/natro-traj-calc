# natro-traj-calc
Trajectory design and simulation tool to verify NASA's trajectory browser and validate hand calculated transfer mechanics.

The transfer portion of the space segment will consist of multiple orbital maneuvers throughout
the deep space flight to Neptune. First, the satellite will be launched from Earth at low inclination and
inserted into a geosynchronous orbit (GSO). The deep-space craft, now free of its initial staging, will circle Earth 
waiting for the right launch window until finally implementing a ΔV burn, changing the circular GSO to a parabolic 
flight path towards Jupiter. Once the vehicle enters the sphere of influence of Jupiter it will assist the effect of 
Jupiter’s gravity well with a small ΔV burn, initiating a hyperbolic gravity slingshot course correction towards Neptune.

The deep space segment consists of the sections of the mission in-between the Earth GSO and
Jupiter, as well as in between the Jupiter gravity assist and the aero-capture maneuver into Neptune's atmosphere.

This code simulates the movements of the bodies around the Sun as separate two body problems, as well as Triton's
movement around Neptune in the Heliocentric coordinate frame. Most importantly, it simulates the first Hohmann transfer
from Earth parking orbit to just inside the Jupiter gravitational SOI.
