# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```

Program to find and display the priority of the operator in the given Postfix expression
Developed by: Krishna Prasad S
RegisterNumber:  212223230108

```
```c

/*#include <stdio.h>*/
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) 
{
    for(int i=0; i<n; i++)
    {
        tat[i] = burst_time[i] + wait_time[i];
    }
    return 0;
}

```

## Output:



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
