B1024 Clone Project (C)2020 Steve J. Gray.
=================== Started May 2020

Intro
-----

This is a project to clone the
Anderson Engineering 1024K Board for CBM-II.
Mike Naberezny purchased a bare board from Bill Degnan and
then scanned it and posted pictures on his web page:

http://mikenaberezny.com/hardware/cbm-ii/b1024-ram-expansion-board/


Component Reference
-------------------

Since the board has no references for the IC's
I have numbered them based on the following:

- With the board oriented with pin 1's on the LEFT or TOP.
- U1 is at the top left.
- Connectors P7 and J6 are below it
- U2 is at the bottom left.
- U3 to U12 are to the right.

The DRAMs are:
- U12 to U19 on the top row
- U29 to U27
- U28 to U35
- U36 to U43 on the bottom row

Then U44 to U47 on the right of the board
P9 and J9 are between U46 and U47


IC PARTS
--------

U1 - 6264
U2 - 74S85

U3 - 74S74
U4 - 74S08
U5 - 74S02
U6 - 74LS393
U7 - 74S153
U8 - 74S153
U9 - 74S153
U10- 74S153
U11- 74S153

U12 to U43 - 41256 DRAM

U44- 74S157
U45- 74S139
U46- 74S157
U47- 74S153


PARTS (From Mike N)
=====

* Sockets:
    - 28 pin x 1 for 6264
    - 16 pin x32 for DRAMs
    - 16 pin x11 for other chips
    - 14 pin x 3 for other chips
* Jumpers
* 41256 DRAMx32
* 6264 SRAM
* 74S02
* 74S08
* 74S74
* 74S85
* 74S139
* 74S153
* 74S157
* 74LS393
* Capacitor 0.1uF x 51
* Resistor 4.7K .25W
* Resistor Networks:
   - 22 ohm 4 section / 8 pin
   - 22 ohm 5 section / 8 pin
   - 4.7K   7 section / 8 pin
   - 4.7K   9 section / 10 pin
   - 10K    9 section / 10 pin
