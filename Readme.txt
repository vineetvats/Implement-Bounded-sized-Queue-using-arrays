Aim: Implement a bounded-sized queue BoundedQueue<T>, using arrays with the following operations:
   To avoid "generic array cannot be created" error, declare the array to be Object[] and
   typecast where needed to avoid type warnings.
   BoundedQueue(int size): Constructor for queue of given size
   boolean offer(T x):	add a new element x at the rear of the queue
			returns false if the element was not added because the queue is full
   T poll():		remove and return the element at the front of the queue
			return null if the queue is empty
   T peek():		return front element, without removing it (null if queue is empty)
   int size():		return the number of elements in the queue
   boolean isEmpty():	check if the queue is empty
   void clear():	clear the queue (size=0)
   void toArray(T[] a):	fill user supplied array with the elements of the queue, in queue order

Team Members:
Manindra Kumar Anantaneni : mxa180038	
Vineet Vats - vxv180008

Prerequisites:
Eclipse Java Oxygen
Java(JDK) 8

Create a java project and create 2 java files in it. One for Interface OurQueue and the other for BoundedQueue.Copy the codes in the respective files.

Inputs and procedure to run the program:
Once you compile and execute(run) the code, the list is printed.
Firstly we have to input the maximum size of the queue as it is a bounded queue.
Then, we have to input the queue size in which we can add that number of element in one go.
Now there are 6 options - 1, 2, 3,4,5 and 6.
Entering 1 will ask for an element to be added at the rear of the list.
Entering 2 removes front element and prints that element.
Entering 3 will print the front element without deleting it.
Entering 4 will print the size of the queue.
Entering 5 will clear the queue.
Entering 6 will Convert it into an array and print it.
Now the updated list with the new elemnt is printed.
