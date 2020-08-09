**Musical Chairs**

Simulated musical chairs game using thread synchronization.

------

``Used semaphores to maintain thread safety``

Each thread acts like a player and tries to acquire a resource, and in each round a thread gets eliminated.

To maintain fairness, all threads start to acquire resources only when signaled.

------
Outputs of sample test cases are provided in text file along with some test files
