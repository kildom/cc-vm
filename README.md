# cc-vm (C C Virtual Machine)

**A tiny virtual machine written in C to execute C code.**

The virtual machine is desined for very small embedded devices.
It takes less than **2KB** of program memory and **32 bytes** of RAM plus whatever you want to give to your guest program.
With it, you can add C-based scripting almost anywhere.

It runs bytecode compiled with modified version of TCC (Tiny C Compiler).
You need to compile the code before passing it to the target device.
In most cases, this is not an issue, since you are using PC to upload such program.
The compiler can also run in a browser, which is useful for some IoT devices.

