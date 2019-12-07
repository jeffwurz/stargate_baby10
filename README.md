# stargate_baby10
 instructions for assembly of the stargate baby10 sequencer


##BOM:
  ```
  3: LM555
  3: 8pin IC socket
  1: CD4017BE
  1: 16 pin IC socket
  1: SMD power switch - SW_POW1
  1: 8ohm speaker - LS1
  12: 470k potentiometers
  20: 1N4148 diodes
  21: THT switches
  10: 3mm LED
  12: 1k bias/555 resistors THT
  1: 1.0 uF Polarized
  1: 10 uF Polarized
  1: 0.01 uF
  1: 0.1 uF
  1: 9v battery holder with leads
  ```
##Assembly:
  ```
  For Frontside mounting: LEDs, Potentiometers, THT Switches

  For Backside mounting: Resistors, Capacitors, IC sockets -> ICs,
    1N4148 Diodes, 9v Battery wires(+ is square pad, - is circular pad)
  ```
##Operation:
  ```
  There are 2 switches that correspond to each step,
   they are located to the left and right of the LED
   for that step.
  Each one is a different function for that step.
    The left switch is to skip the step, while the
     right switch is to reset at that step*

  There is also a skip enable switch located above the
   3rd step's potentiometer. To enable position the
   switch towards the outside edge of the board.
  ```
