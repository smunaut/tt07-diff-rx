![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg)

# Tiny Tapeout 07: Differential Receiver test

This is designed to test a differential receiver with the following
target specifications:

* Up to 500 Mbps 
* -0.1V to 0.6V input common mode
* 150mV to 600mV differential amplitude

Both a clock and data are expected at the input with the clock being
90 deg out of phase (to center transitions in the data eye).

Output is deserialized to 16 bits.
