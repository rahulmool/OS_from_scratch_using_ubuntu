*Concepts you may want to Google beforehand: stack*

**Goal: Learn how to use the stack**

The usage of the stack is important, so we'll write yet another boot sector
with an example.

Remember that the `bp` register stores the base address (i.e. bottom) of the stack,
and `sp` stores the top, and that the stack grows downwards from `bp` (i.e. `sp` gets
decremented)

This lesson is quite straightforward, so jump ahead to the code.

I suggest that you try accessing in-stack memory addresses by yourself, 
at different points in the code, and see what happens.

<img src="https://github.com/rahulmool/OS_from_scratch_using_ubuntu/blob/main/04-bootsector-stack/Screenshot%20from%202022-04-27%2015-50-35.png?raw=true"></img>