# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program for getting integer input from the user using BufferedReader.

## ALGORITHM :
1.	Start the program.
2.	Import java.io.*.
3.	Create an InputStreamReader and wrap it in a BufferedReader.
4.	Prompt the user to enter an integer.
5.	Read the input using readLine().
6.	Convert the string input to an integer using Integer.parseInt().
7.	Display the integer.
8.	Handle exceptions like IOException and NumberFormatException.
9.	End the program


## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: Surendhar K
RegisterNumber:  212222040166
*/
```

## Sourcecode.java:
```
import java.io.*;
public class Sample
{	
public static void main(String [] args) throws IOException
{
    InputStreamReader inp=new InputStreamReader(System.in);
    BufferedReader b=new BufferedReader(inp);
    int res=Integer.parseInt(b.readLine());
    System.out.println("Entered Integer : "+res);	
}					
}

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/4fc88150-8fdd-47fb-8e32-1919526d47af)


## RESULT:
Thus, the Java program reads an integer input from the user using BufferedReader and displays the result as specified.

