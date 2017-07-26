## Multithreaded FIFO Gate

Originally published: 2008-08-13 05:32:48
Last updated: 2008-09-08 08:29:14
Author: Anand 

While programming with multiple threads, sometimes one needs a construct which allows to suspend the execution of a set of running threads. This is normally required by an outside thread which wants to suspend the running threads for performing a specific action. The threads need to resume after the action in the same order in which they got suspended. 