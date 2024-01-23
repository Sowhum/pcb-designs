ESP 32 WROOM 32E is powered using a 3.3V coin cell wired through a SPST switch 

The 32E has no dedicated pins , here i used GPIO pins for most of the connections including SDO,SDI,SCK and powering the components with 3.3V

LCD connection was done by following the provided tutorial and comparing pinouts of  ESP 32 in the turorial with the 32E

BMP280 connection was done by following the example given in it's datasheet for i2C

Due to limitations of size and the LCD taking most of the space in front, all other components except the switch have been placed on the back

Two of these are surface mounts(the ESP32 and the BMP280) so vias are used for most of their connections

The through hole components under the LCD have enough clearance



