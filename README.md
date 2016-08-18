# Donnie's PCB

This repository has all files related to Donnie's hardware (PCB design, schematics, eletrical diagrams, gerber files, BOM files). Donnie has two daugther boards (or 'shields'). One for the Arduino Mega (see ard-shield dir) and the other for the Raspberry Pi (see rasp-shield dir). 

## Manufacturing the boards

### Send the Gerber for manufacturing

If you just want to manufacture these boards as they are, we recommend the following steps:

 1. Send the Gerber ZIP files ([ard-shield](ard-shield/gerbers/ard_shield-160322-gerbers.zip) and [rasp-shield](rasp-shield/gerber_files/rasp_shield-gerber_files-160118.zip)) to manufacture to Seeedstudio. You should use the following tutorial [Fusion PCB Order Submission Guidelines](http://support.seeedstudio.com/knowledgebase/articles/422482-fusion-pcb-order-submission-guidelines)

### Assembly

 After you receive the PCBs, then follow these steps to assemble the boards:

 1. First of all, separe and buy the components indicated in BOM file ([ard-shield](ard-shield/BOM.txt) and [rasp-shield](rasp-shield/BOM.txt));
 2. Print the PDF schemmatic and BOM file;
 3. Place and weld the componnects in the PCB with the BOM's indicated PART.

## Change the PCB Design

If you want to change the PCB design, we recommend to use Eagle version XYZ.


