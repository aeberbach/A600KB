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

Warning! There is a bug in this keyboard design. Many people have built it and never noticed, but this can be a problem with software (trackers) that uses the two keys affected. The PCB as-is should be modified according to the diagram shown here.
![How to fix swapped keys](/A600-kb-fix.jpg?raw=true "Required Modification")
One of these days I will update the PCB files but until then this will be useful to those who have one and notice a problem.
