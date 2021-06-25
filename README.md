
- Nachos Operating System

Nachos, is instructional software for teaching undergraduate, and potentially graduate level operating systems courses. It was developed at the University of California, Berkeley, designed by Thomas Anderson, and is used by numerous schools around the world. Originally written in C++ for MIPS.

Nachos - Synchronization

Processes sometimes (in fact frequently) need to communicate with other processes. There needs to be a well-structured way for this communication to occur which does not rely on interrupts. There needs to be a well defined way of passing information between processes, coordinating process activity. There are three high level synchronization techniques which provide Synchronization. They are Semaphores, locks and Monitors & condition variables.

In this project, we have three server threads, Server 0, Server 1, and Server 2; each server reads from its own designated file that contains only partial data of an image and writes the data to a shared buffer, Buffer. Two client threads then read from the buffer and print the content of the buffer to screen, which results a reconstructed ASCII image of a cartoon character. Implement the Server() function for the three servers and the Client() function for the two clients.
