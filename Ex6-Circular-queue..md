# Ex6 Dequeue Elements from Circular Queue
## DATE:
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```

Program to delete three elements from the filled circular queue
Developed by: Krishna Prasad S
RegisterNumber:  212223230108

```
```c

/*#include <stdio.h>

#define SIZE 5

int items[SIZE];
int front = -1, rear = -1;
*/
int deQueue() {
  int element = items[front];
  if(isEmpty())
  {
      printf("Queue is empty");
  }
  else
  {
      front = (front+1)%SIZE;
  }
  return element;
}

```

## Output:



## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
