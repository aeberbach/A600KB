# A600KB: Mechanical keyboard project for Amiga 600

Like my A1200 project (see my other repos) this is a mechanical keyboard for an Amiga computer.

To make one you need:
- PCBs, which you can make by sending the contents of the 'fab' folder to your local PCB maker.
- 3D printed parts: the STL files are in the STL folder. I used a Prusa MK3S 0.25mm nozzle, Urban Grey PETG.
- 78 MX PCB-mount switches
- 32-way FFC connector (Mouser part number 538-52044-3245)
- 32-way ribbon cable (Mouser part number 538-15168-0400)
- keyswitch stabiliser for Tab and Enter keys
- one 3mm LED for CapsLock
- keycaps

For more details about design choices and putting it together please see the article on grayunicorn.com. 

Enjoy!

May 2022 Update - this is now release 2. Apart from correcting swapped keys that existed in revision 1 (see below) I made a lot of traces simpler. I used KiCAD 6 for this, it just keeps getting better. If you build a revision 2 I would love to hear about it.

Revision 1 Errata:
Many people have built it and never noticed. That goes for me too - one person contacted me and said they were having trouble with some music tracker software because it relies on the keys that are not in the right place. I had not noticed because I had not been using software that relied on those
keys - sorry if you were affected! The revision 1 PCB should be modified:

- Line 5: disconnect from MX63 (< ,) column; connect to MX79 (" ') column
- Line 7: disconnect from MX79 (" ') column; connect to MX63 (< ,) column
- Line 23: disconnect from MX79 (" ') row; connect to MX63 (< ,) row
- Line 26: disconnect from MX63 (< ,) row; connect to MX79 (" ') row

The PCB has been revised to revision 2 (the same as Commodore's schematic) now so this is fixed, but if you have a revision 1 and notice the ' and , appear to be swapped then you may need to apply this change.