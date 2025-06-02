# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to display the added elements from the Priority Queue and to insert a particular element into the Priority Queue and then display the elements.(Use offer() method).


## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: Surendhar K
RegisterNumber:  212222040166
*/
```

## Sourcecode.java:

```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("Display the element of Queue:");
		System.out.println(pQueue);

		
	}
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/197adc1b-59d4-4ca1-bf8a-9a263da6fdb2)


## RESULT:
Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method )was executed successfully.


