#Use of Operational Amplifiers (Op Amps)

An operational amplifier is a device that takes 2 inputs, measures the difference between them, then outputs this voltage increased
by a factor known as "gain". The gain of an operational amplifier is the extent to which the difference in voltage between its two inputs
is increased. The two inputs of are normally identified as the "inverting" and "non-inverting", indicated on the schematic by "-" and "+" respectively.
An op-am also requires two different supply voltages to function. These supplies determine the output range of an op-amp, as it will be unable to exceed these voltages, regardless of its gain. The gain of an op-amp is typically 
on the order of 100,000. In other words, if the supply were large enough, a 1 mV difference between the inputs would result in a 100V output

\begin{center} \includegraphics [height=5cm] {img/opamp.png} \end{center}

In an analogue circuit, a gain of this magnitude is generally not useful, as the op-amp will saturate for extremely small signals. In an ideal op-amp, saturation means that the output is equal to the supply voltage. However, in the case of a real op-amp, this is normally slgihtly lower than the supply voltage. A common solution to this problem is to build a "feedback loop". This is where the output of the op-amp is connected back to one of the inputs through a resistor. Several configurations of this are possible, however, in all cases the feedback is used to reduce the gain.

However, In circuits where analogue and digital signals are both present, the saturation of an "open loop" op-amp can sometimes be useful. An "open loop" configuration has no connection between its input and its output. This is the condition under which an op-amps gain is usually measured.

\begin{center} \includegraphics[height=5cm] {img/comparator.png} \end{center}

Try building the circuit shown above:
*Try the circuit for different input voltages
*What happens if you change the values of R1 and R2

What do you think is happening here? Do you think that you could use it for your robot?
