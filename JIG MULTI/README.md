# JIG MULTI
PCB for JIG for PCH-100x, VTE-100x and PCH-200x PSVITA

* Currently supprorts PCH-1XXX/PDEL-100x, VTE-100x and PCH-2xxx PSVITA at both 3.3V and 5V
Throughhole design only.

* * CAUTION (5V circuit only) Be aware that some UART modules advertised as 5V or with a jumper to 5V do NOT shift the power levels for UART TX/RX which will operate at 3.3V, Please measure voltage using a multimeter on your UART module between TX and GND, if it runs at 3.3V Replace R1 to a 1K ohms resistor in the 5V design.

![image](https://github.com/mathieulh/PSVITA-JIG-PCB/assets/203427/1b0cc13f-988e-4eb3-9562-280b400e023a)
