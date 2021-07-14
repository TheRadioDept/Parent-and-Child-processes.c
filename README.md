# Parent-and-Child-processes.c
Just to see how fork() method works. 
It does not work on Windows machine, so you have to use Linux only. 
The reason why it doesn't work is <unistd.h> and fork() method itself. They are part of POSIX standard.
https://stackoverflow.com/questions/9612315/why-does-my-compiler-not-accept-fork-despite-my-inclusion-of-unistd-h See the link for better understanding. 
