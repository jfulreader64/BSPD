# BSPD
Here is the BPSD I worked on for Clarkson Formula Electric. The Schematic is a modified version of the FSG Reference Schematic. PCB is original.
Design files are all in altium
This board takes in two signals, a brake transducer and a current sensor. If hard braking is applied i.e the brake transducer is above a sertain threshold, and the current sensor reads a value over a set KW limit then this circuit will shut down the FSAE electric car. The BSPD gives out a 5 volt signal when sensors are in range to close a relay in the shutdown circuit.
