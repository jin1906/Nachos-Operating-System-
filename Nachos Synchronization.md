# Nachos Operating System
# © 2018 TAN RUAN ZHEN XIN ALL RIGHTS RESERVED

Nachos, is instructional software for teaching undergraduate, and potentially graduate level operating systems courses. It was developed at the University of California, Berkeley, designed by Thomas Anderson, and is used by numerous schools around the world. Originally written in C++ for MIPS.

# Nachos - Synchronization

Processes sometimes (in fact frequently) need to communicate with other processes. There needs to be a well-structured way for this communication to occur which does not rely on interrupts. There needs to be a well defined way of passing information between processes, coordinating process activity. There are three high level synchronization techniques which provide Synchronization. They are Semaphores, locks and Monitors & condition variables.

In this project, we have three server threads, Server 0, Server 1, and Server 2; each server reads from its own designated file that contains only partial data of an image and writes the data to a shared buffer, Buffer. Two client threads then read from the buffer and print the content of the buffer to screen, which results a reconstructed ASCII image of a cartoon character. Implement the Server() function for the three servers and the Client() function for the
two clients.

![screen shot 2018-12-19 at 8 01 06 pm](https://user-images.githubusercontent.com/28322834/50257797-d39bf000-03ca-11e9-8f50-2c4d1954c4ca.png)


![1](https://user-images.githubusercontent.com/28322834/50257942-794f5f00-03cb-11e9-9731-0052d3d9e155.png)

![1 1](https://user-images.githubusercontent.com/28322834/50257986-ac91ee00-03cb-11e9-93fa-4fbbda378c63.png)

![1 3](https://user-images.githubusercontent.com/28322834/50257991-b1ef3880-03cb-11e9-890f-12366c1321e2.png)

![1 2](https://user-images.githubusercontent.com/28322834/50257992-b1ef3880-03cb-11e9-9b93-ea17d856a851.png)
