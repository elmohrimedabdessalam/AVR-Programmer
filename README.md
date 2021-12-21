# AVR-Programmer
## Description :
AVR-programmer app allows you to program usual AVR microcontrollers. this app offers to choose the programmer type, baud rate, available COM port, and MCU. 
the use is by calling the app from inside Atmel Studio or Microchip Studio as an external.
## Setup AVR-Programmer in Atmel/Microchip Studio :
### 1-Download and extract :
after Downloading and extracting the AVR-Programmer folder, drop the file in a directory that you remember after, (for example Program Files (x86)).
### 2-Adding the AVR-Programmer as an external tool:
- Go to the menu bar `Tools -> External Tools`.
- Click on `Add` button to add new external tool.
- fill the `Title` field by AVR Programmer or the name of your choice.
- In the `Command` field, browse to`AVR_Programmer.exe` in AVR-Programmer folder (for example
 `"C:\Program Files (x86)\AVR_Programmer\AVR_Programmer.exe"`). 
- fill the `Arguments` field by `-P $(ProjectDir)  -t $(TargetName)`.
- Click `OK` to save your tools.
- You find your tool in `Tools -> AVR Programmer`. 

