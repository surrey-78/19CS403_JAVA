# Ex.No:7(C)             THREAD IN JAVA
## AIM:
To develop a Java program to create a Thread using the extends Thread method and get a thread integer number from the user.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Declare an integer variable to store the thread count 
-	b) Use a constructor to accept the count value
-	i) Override the run() method:
-	ii) Print "Thread Count: " followed by the number
4.	In the `main` method:
-	a)  Create a Scanner object for input
-	b) Prompt the user to enter an integer number
-	c) Create an object of MyThread by passing the number
-	d) Start the thread using start()


5.	End





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:

```
   import java.util.*;
    public class Multi extends Thread
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        int count=sc.nextInt();
        System.out.println("Thread Count: " +count);  
    }  
    public static void main(String args[]){  
    Multi t1=new Multi();  
    t1.start();  
     }  
    }
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/191cbb5c-953c-4f81-87b1-5bc1129a6f9d)


## RESULT:
Thus, the Java program for the creation of a Thread using the extends Thread method and user input was executed successfully.







