## Misc 3 Challenge

This one was interesting. The challenge was introduced with a elf file named misc300.elf and a hint saying “Key to OPKG is your Flag”. The moment I was ELF file, one thing that came to my mind was reverse engineering. The tool I used for this challenge is binwalk. Extracted the elf file using binwalk: binwalk –e misc300.elf An extracted folder will be created. Just go to the _misc300.elf.extracted/cpio-root/etc/opkg/keys path. The key was stored in a file “af22f7a88858c8e9”.  


So the flag for misc3 was:  

    flag{ RWSvIveoiFjI6WS/h3J8Us0wUEjA53cQLuHJEwOD/sT5JsGvguZjlKmU}
    
 ![](https://github.com/architaa/hackim8-writeup/blob/master/images/misc3.PNG?raw=true) 
