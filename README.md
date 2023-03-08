# Parking-System-Using-Semaphore

In this project I are working on two major concepts of operating system:
1.	Semaphore: a semaphore is a variable or abstract data type used to control access to a common resource by multiple threads and avoid critical section problems in a concurrent system such as a multitasking operating system.
A useful way to think of a semaphore as used in a real-world system is as a record of how many units of a particular resource are available, coupled with operations to adjust that record safely (i.e., to avoid race conditions) as units are acquired or become free, and, if necessary, wait until a unit of the resource becomes available.
In our project we will use semaphore to ensure that only one vehicle gets to be parked at one time and all other have to wait until their turns come. As getting two vehicles (process) in the automatic machine will cause a deadlock that’s why to avoid deadlock we are using semaphore.
2.	FCFS: First come first serve (FCFS) scheduling algorithm simply schedules the jobs according to their arrival time. The job which comes first in the ready queue will get the CPU first. The lesser the arrival time of the job, the sooner will the job get the CPU. FCFS scheduling may cause the problem of starvation if the burst time of the first process is the longest among all the jobs.
I using FCFS synchronization technique which will ensure that only that vehicle align to the queue according to the order they came. 
