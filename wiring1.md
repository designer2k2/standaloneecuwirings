# vr6 to black

http://www.ecumaster.nl/20695-thickbox_default/ecumaster-emu-black.jpg

http://www.montecarlomagic.de/Tipps&Tricks/Pinbelegung%20VR6%20Motorsteuergeraet%20_Mj.95.pdf

Black:

|pin|function|function|pin|
|--|--|--|--|
|1|ignition coil #5|not used|-|
|2|EGT in #1|EGT1|--|
|3|Knock Sensor in #1|Klopfsensor|34|
|4|Analog in #2|?|?|
|5|CLT In|Kühlmitteltemperatur|14|
|6|WBO Vs|?|?|
|7|Camsync in #2|?|?|
|8|Primary trigger|G28 Geber Motordrehzahl|67|
|9|Flex fuel in|not used|-|
|10|Switch #1 in|?|?|
|11|RS232 TXD|?|?|
|12|CAN H|?|?|
|13|Constant +12V|Dauerplus|Klemme 30|
|14|Ignition coil #4|not used|-|
|15|EGT in #2|EGT2|?|
|16|Knock Sensor in #2|Klopfsensor|57|
|17|Analog in #3|?|?|
|18|TPS in|Drosselklappen Potentiometer|40|
|19|WBO Ip|?|?|
|20|VSS in|?|?|
|21|Camsync in #1|G40 Nockenwellenhallgeber|44|
|22|WBO Rcal|?|?|
|23|Switch #2 In|?|?|
|24|RS232 RXD|?|?|
|25|CAN L|?|?|
|26|+5V Supply|?|?|
|27|Power Ground|Masse|Klemme 31|
|28|ECU Ground|Masse|Klemme 31|
|29|Sensor Ground|Masse|68|
|30|Analog in #4|?|?|
|31|Analog in #1|?|?|
|32|IAT In|Saugrohrtemperatur|36|
|33|WBO VGND|?|?|
|34|+5V Supply|?|?|
|35|Analog in #5|?|?|
|36|Switch #3 In|?|?|
|37|Analog in #6|?|?|
|38|Sensor Ground|Masse|33|
|39|Sensor Ground|Masse|10|

Grey:

|pin|function|function|pin|
|--|--|--|--|
|1|Ignition coil #6|not used|-|
|2|H-Bridge #1 Winding A|?|?|
|3|H-Bridge #2 Winding A|?|?|
|4|AUX 6|?|?|
|5|AUX 3|?|?|
|6|Injector #4|Einspritzventil #4|2|
|7|Injector #1|Einspritzventil #1|24|
|8|Ignition Coil #1|Zündblock #2|8|
|9|Ignition Coil #3|Zündblock #4|52|
|10|H-Bridge #1 Winding B|?|?|
|11|H-Bridge #2 Winding B|?|?|
|12|AUX 5|?|?|
|13|AUX 2 / Injector #8|?|?|
|14|Injector #5|Einspritzventil #5|3|
|15|Injector #2|Einspritzventil #2|25|
|16|Ignition Coil #2|Zündblock #3|60|
|17|Power Ground|Masse|Klemme 31|
|18|Ignition +12V|Zündplus|Klemme 15|
|19|WBO Heater|Lambda Heizung|?|
|20|AUX 4 / Tacho|?|?|
|21|AUX 1 / Injector #7|?|?|
|22|Injector #6|Einspritzventil #6|4|
|23|Injector #3|Einspritzventil #3|26|
|24|Power Ground|Masse|Klemme 31|

Leerlaufpoti 62
DK Sensormasse 41
Gebermasse 10
DK Motor 27+ 53-

G70 Luftmasse 17 16  (4 2)

Geschwindigkeitssignal 65

Inputs:
Clutch
Brake
Oiltemp
Fuel press
Oil press
Map Switch (Manual switch)

Outputs:
Fuel Pump
Speedometer
Shiftlight
Check Engine Light
