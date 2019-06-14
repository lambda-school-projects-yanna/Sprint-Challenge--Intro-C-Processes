**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**

start: the initial state of a process

ready: process is ready for the OS to assign it a processor. 

running: after assignment to a processor when the process is executing

waiting: processor is waiting for the availability of something needed

terminated: once process is done executing, or is terminated, it becomes ready to remove from main memory. 


**2. What is a zombie process? ow does a zombie process get created? How does one get destroyed?**

leftover bits of dead processes that haven’t been cleaned up properly.
If a parent process isn’t programmed properly and never calls wait(), its zombie children will stick around in memory. You cant kill a zombie process but you can kill the parent process that created it.


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

Platform independent and faster performance 