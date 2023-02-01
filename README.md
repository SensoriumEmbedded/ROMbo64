# ROMbo64
 Replacement Kernal, Character, and BASIC ROMs in a single EEPROM
 I had a working proto and was finalizing logic when I came across this project: https://github.com/hbekel/reprom64
 Based on this, I addopted some of their design choices into mine, full credit goes to the REPROM64 project.  In fact, that project covers more C64/128 models, and is therefore a more thorough solution
 Mine is a bit more compact PCB, but will only work (without wires) with the 250407 and 250425 C64 PCA versions.  Other versions would have to extend the BASIC and Char ROM Cip Select lines to the ROMbo64 board.
 Rom selection can be done by jumpers, switched, or driven from a microcontroller such as Arduino.
 
 