# DWARF-SH33T 

After discussion it appears that somehow maybe people can be interested by this sh33t. 
I only decided to work on this implementation to learn a little bit about how to implement a processor inside IDA. 
IMHO DWARF virtual processor "*architecture*" is the simplest way to learn about creating processor. 

I met a lot of IDA crashes (including weird internals error) while doing stupid stuff with my fingers.
Good way to do bug hunting: being the most stupid and generate crashes l33t people won't see. Sometime you can turn a weakness into a tale.  LAULE 


##Install 

Place the swaggydwarf.py file inside your ida/procs/ repository. 
Load your binary and select inside the list the corresponding name. 
Consider the base address to avoid disappointment. 

ALT+7 to launch emu-dwarf.py
Please read quickly the script and adapt it to your need before. 
emu-dwarf is stupidly printing the stack for each instruction it executes. (load the binary dump, and init() your stack'
You can *symbolise* your stack entries, but don't think you will get a SMT models (but if you do feel free to PR LEAULE). 


##Disclaimer 

My code is sh33t. 
I did a little of test, but it is far to be enough. 
My purpose here is to help beginners like me to investigate that kind of stuff. 
Emulation worst nothing, but it is better than nothing to start. 


##BUG 

LIT8 insn is not working, so it will put 0 instead handy isn't ?  


##Beautiful screenshot 

![dwarf-examples](/images/dwarf.png)

