Title:

**GPIO pin ruggedizer**

Taken from https://www.rugged-circuits.com/





**Use Case and Warnings:**

This is used on all the rugged-circuits(tm?) boards as a way to protect I/O pins from overvolting, shorting to ground, and shorting to each-other.

The resettable (PTC) fuse has internal resistance. This means you may not need a current limiting resistor for powering led's.


**What this circuit does:**

A 5.1 Volt reverse-biased Zener diode protects from overvolting (up to 24V) while a resettable fuse protects from current spikes and shorting.

![](am010_iopinmodel.gif)


**Key Parts:**

1N4733A   5.1V Zener Diode - https://www.sparkfun.com/products/10301

300ma/200ohm (or closest possible) PTC- Sparkfun sells this one: https://www.sparkfun.com/products/8357
