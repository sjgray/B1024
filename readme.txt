B1024 Clone Project (C)2020 Steve J. Gray.
=================== Started May 2020

Intro
-----

This is a project to clone the
Anderson Communication Engineering 1024K Board (Rev A) for CBM-II.

Mike Naberezny purchased a bare board from Bill Degnan and
then scanned it and posted pictures on his web page:

http://mikenaberezny.com/hardware/cbm-ii/b1024-ram-expansion-board/

Thank-you to Mike for providing this information!


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


PARTS LIST
==========

Sockets:
--------
  - 28 pin x 1 for 6264
  - 16 pin x32 for DRAMs
  - 16 pin x11 for other chips
  - 14 pin x 3 for other chips

ICs:
----
U1 - 6264 SRAM, 8Kx8
U2 - 74S85   4-bit Comparator
U3 - 74S74   Dual D positive edge Flip-Flop
U4 - 74S08   Quad 2-input AND
U5 - 74S02   Quad 2-input NOR
U6 - 74LS393 Dual 4-bit Binary Counter
U7 - 74S153  Dual 4 to 1 selector
U8 - 74S153  Dual 4 to 1 selector
U9 - 74S153  Dual 4 to 1 selector
U10- 74S153  Dual 4 to 1 selector
U11- 74S153  Dual 4 to 1 selector

U12 to U43 - 41256 DRAM 256Kx1

U44- 74S157  Quad 2 to 1 Multiplexer
U45- 74S139  Dual 2 to 4 line decoder
U46- 74S157  Quad 2 to 1 Multiplexer
U47- 74S153  Dual 4 to 1 selector

Capacitors:
-----------
C1 to C51 - 0.1uf disc

Resistors:
----------
R1        - 22 ohm
R2, R3    - 4.7K
R4        - 22 ohm

RN1 - 4.7K   SIP 10-pin Bussed 9 Resistor Network
RN2 - 22 ohm SIP 10-pin Separate 5 Resitors Pack
RN3 - 22 ohm SIP 10-pin Separate 5 Resitors Pack
RN4 - 22 ohm SIP 8-pin  Separate 4 Resitors Pack
RN5 - 22 ohm SIP 8-pin  Separate 4 Resitors Pack
RN6 - 4.7K   SIP 8-pin  Bussed 7 Resistor Network
RN7 - 10K    SIP 10-pin Bussed 9 Resistor Network
RN8 - 10K    SIP 10-pin Bussed 9 Resistor Network
RN9 - 4.7K   SIP 8-pin  Bussed 7 Resistor Network

Jumpers/Headers:
----------------
J1 - 2-pin 90 degree male header "RESET" 
J2 - 3-pin 90 degree male header "0FFF/0800 EN"
J3 - 3-pin 90 degree male header "LED"
J4 - 3-pin 90 degree male header "RAM ROM" 
J5 - 60-pin vertical female header 
J6 - 60-pin vertical female header
J9 - 40-pin vertical female headerc
P6 - 60-pin vertical male header
P9 - 40-pin vertical male header
