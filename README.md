# kyblOS
distributed by **kybl enterprise**
 - OpenAI + denyyys creating an operating system
 - references to gravity bong 
 
 
### How does it work?
This OS prints the string "Kybl Enterprise" to the screen.
It loads the address of the string into the SI register and then call the printf function
The printf function loops through the characters in that string and prints them one by one with an interrupt call

### Why only 512B ?
This program is only 512B in size because the x86 architecture requires programs to be loaded at a specific segment address, and the default address is 0x7c00 which is 512 bytes in size.
