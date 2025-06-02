# Ex.No:7(E) THREAD SYNCHRONIZATION

## AIM:
To write a Java program to display even numbers up to the given range using a synchronization block.
## ALGORITHM :
1.	Start the program.
2.	Create a class named Table.
3.	Inside the class, define a method void Even(int n):
     a.	Use a synchronized block to ensure only one thread prints at a time.
     b.	Inside the synchronized block:Loop from 1 to n,Print even numbers,Use Thread.sleep(400) inside the loop to pause after printing each number.
  	
4.	Create another class (e.g., EvenNumberThread) that extends Thread.
      a.	Define a constructor to accept a Table object and a number.
      b.	In the run() method, call the Even(n) method from the Table class.

6.	In the main method:
      a.  Create one Table object.
  	 b.  Create multiple thread objects, passing different range values (e.g., 10, 20).
  	 c.  Start both threads.
8.	End the program.	



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:

```
class Table{  
    void Even(int n){
        synchronized(this)
        {
            int i=2;
            System.out.print("List of Even numbers for "+n+" : ");
            while(i<=n){
                System.out.print(i+" ");
                i=i+2;
                
            }
            System.out.println();
            try{
                Thread.sleep(400);
                
            }
            catch(Exception e){
                System.out.println(e);
                
            }
            
        }
        
    }
    
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/f74b34d6-5bd6-42e7-98fc-4c44120275ed)




## RESULT:

Thus, the Java program was successfully executed to display even numbers using a synchronization block, demonstrating thread-safe access to shared resources.


