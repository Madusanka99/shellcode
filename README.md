# shellcode
Shell code for get a shell (/bin/bash)

shell.asm
https://github.com/Madusanka99/shellcode/blob/master/Capture1.JPG

Assembling and linking
https://github.com/Madusanka99/shellcode/blob/master/Capture2.JPG

Run the code and check the exit status
https://github.com/Madusanka99/shellcode/blob/master/Capture3.JPG

This step is to dump the shellcode's opcodes that are of main concern to us as we need opcodes to attach the shell code to the executable
lets dump the code with objdump

https://github.com/Madusanka99/shellcode/blob/master/Capture4.JPG
As we see there are lots of nuls out there in the opcodes so we need to remove that because as we will be using this shellcode to run it in a executable
