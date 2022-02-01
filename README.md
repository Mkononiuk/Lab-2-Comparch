# Lab-2-Comparch
Lab 2 for Computer Architecture at Rowan University. 

This is the Readme for lab 2
This statemachine functions by updating on the positive edge of the clock cycle.
A register is in the code to store the value of the current state and the next state
The states will go up if the input is in the order 1001
the value st_out will go up as the states go up - 000, 001, 010, 011, 100
each state is linked to an st_out value

The code will not function if the clock is not set
for this reason, the code force clock 1 0ns, 0 50ps -repeat 100ps should be executed so that the clock cycle is active
Reset should be forced to 1 and then to 0
then, I is the input
I should go in the order 1001 with a "run" in between each force so that the code updates
after the last 1 is ran, F, the output, should be 1 for a clock cyce
