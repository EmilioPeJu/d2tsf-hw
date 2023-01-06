# Diamond II TimeStamp Feeder Hardware

This repository contains the PCB design for the board that obtains timestamps
from a GPS receiver (Ublox RCB-F9T) and pushes it to an EVG.

The output signals are: PPS, 1MHZ, SHIFT0 and SHITF1

## Known issues
- With some power supplies, the RCB-F9T can get into an unstable state at start
time. Somehow, Disconnecting TP2 makes the problem go away. It is possible that
this issue might be mitigated by using a better voltage regulator.
