# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To write a Java program to demonstrate control flow of try-catch-finally clause when NullPointerException occurs in the try block and is handled in the catch block.


## ALGORITHM :
1.	Start the Program
2. Import java.util.*
3.	Define class `HelloWorld`:
-	a) In the main method, declare and initialize a string variable to null
4.	Use `try` block to:
-	a) Call a method (e.g., length()) on the null object to deliberately cause a NullPointerException
5.	Use catch block to handle NullPointerException:
-	a) Print the exception message
6.	Use `finally` block to:
-	a) Print "Finally block executed"
7.	After the `try-catch-finally` block, print "Outside try-catch-finally clause"
8.	End



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:
```
public class HelloWorld {
    public static void main(String[] args) 
    {
        try
        {
           String str=null;
           System.out.println(str.length());
        }
         
        catch(NullPointerException ex)
        {
            System.out.println("Exception: " +ex);
        }
         
        finally
        {
            System.out.println("Finally block executed");
        }
        System.out.println("Outside try-catch-finally clause");
    }
}
```      





## OUTPUT:
```
Test	           Expected	                                      Got
1         Exception: java.lang.NullPointerException    Exception: java.lang.NullPointerException
          Finally block executed                       Finally block executed
          Outside try-catch-finally clause             Outside try-catch-finally clause 
```


## RESULT:
Thus, the Java program to demonstrate control flow of try-catch-finally clause when NullPointerException occurs in the try block and is handled in the catch block was executed successfully.





