# thread-safe-counter

![image](https://user-images.githubusercontent.com/59716691/121801532-c518b180-cc72-11eb-84f5-8fd547ece7ad.png)
mutex





![image](https://user-images.githubusercontent.com/59716691/121801540-c9dd6580-cc72-11eb-8285-cc6216943823.png)
semaphore


Mutex is a mutual exclusion technique used to synchronize access to resources and is created with a unique name when the program starts. Mutex can only use Mutex at the same time and only this thread can release Mutex.

Semaphore, on the other hand, is a signalling mechanism and differs from mutex in that even threads without locking can be unlocked by sending a signal.

Semaphore took much longer. 
This is because more than n cases can occur in semaphore, while mutext implements both lock and unlock.
