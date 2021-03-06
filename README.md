# SFX-100-Breakout-Board
An Arduino Leonardo shield to simplify the wiring of SFX-100 serial port connectors

For more information about the SFX-100 project, please visit:
https://opensfx.com/

The "Group Buy Edition" is the latest and greatest.

The prototype works fine and uses the RJ45 connector for the E-stop instead of a screw terminal.


Releases
========
v1.35 April 24, 2019
A small modification to allow support for external power supplies higher than +5v. Not really necessary for our use case as powering by USB works fine and is typical for this application. But just in case someone out there does it differently for some reason. :)


========
v1.34 April 6, 2019
Group buy edition

This is the version of the board that was manufactured for the Group Buy.

* Replaced the modular jack with a screw terminal connector for simplicity and cost reduction.

* Removed JP1. You can shunt the screw terminal to test.

* DB25 connectors are now more symmetrical on the board for a cleaner design

* Board traces simplified and vias eliminated.

* Trace thickness increased

* Added additional holes for M3 mounting

* Updated enclosure


========
v1.32 March 23, 2019
Intial public release

J1 is a modular connector for running an Ethernet cable to your e-stop. You need to connect the wires from pins 1 and 8 to your e-stop switch.

If you are not using an e-stop, you must install a shunt jumper across JP1 to enable the circuit.

