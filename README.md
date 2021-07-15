# Automatic-Parking-using-Semaphores

With the increasing number of cars and traffic, it has become a major problem to find place for parking cars in public places such as market places or malls or any famous place.
 
To deal with this problem we have come up with an idea for automatic parking system. This is an efficient way of parking cars using semaphore and first come first service for four-wheeler and two-wheeler separately. 

With this project we will have an efficient way of parking the cars and this will help to reduce the car parking traffic on streets. This is a much cheaper and convenient way of parking.

# About 

We are incorporating two main concepts of operating systems in our project which are: 

**Semaphore**: 
A semaphore, in its most basic form, is a protected integer variable that can facilitate and restrict access to shared resources in a multi-processing environment. The two most common kinds of semaphores are counting semaphores and binary semaphores. Counting semaphores represent multiple resources, while binary semaphores, as the name implies, represents two possible states (generally 0 or 1; locked or unlocked). wait() was called (meaning to decrement) and signal() was called V (meaning to increment). In our project we will use semaphore to ensure that only one vehicle gets to be parked at one time and all other have to wait until their turns come. As getting two vehichle (process) in the automatic machine will cause a deadlock that’s why to avoid deadlock we are using semaphore. 

**FCFS Synchronization**:
To avoid deadlock other process have to wait until the vehicle in the automatic machine gets parked. So, to synchronize the order and avoid any confusion we are using First Come First Serve Synchronization which will ensure that the vehicles align in the queue according to the order they came.

# Screenshots

![image](https://user-images.githubusercontent.com/79261660/125745747-99097b35-7c9a-4dac-8e1c-e7a2e89e7691.png)


![image](https://user-images.githubusercontent.com/79261660/125745727-762a93ff-c33b-49ee-99d5-4d9f4efec902.png)
