Initial schematic and gerbers for a Gotek compatible with an Artery AT32F435RGT7 chip and a 26 Pin FFC connector.
Used SFRKC30.AT4.35 PCB for most of the schematic and layout but used SFRC2D.B PCB for the 26 Pin FFC connections.
Used photographs and a multimeter along with removing U1 and U3 on the SFRKC30.AT4.35 to get to the traces underneath.
Where possible I followed the original PCB routing of the SFRKC30.AT4.35 but Kicad has some different rules for trace widths (between pins 5&6 of U8, which isn't fitted for FlashFloppy).
Included all non pops so that the ibom displays everything.
U8 is not fitted for use with FlashFloppy.]
LEDs 3 and 5 are not normally fitted.
Added ibom (bom/ibom.html).
Restructured folders

Works as a replacement for the floppy in a TDS3052 Oscilloscope. Just needs a very slim case (13mm)
