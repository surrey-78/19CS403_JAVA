# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a java program to append a NUMBER in a file “testout.txt” using Writer.


## ALGORITHM :
1.	It creates a file testout.txt, writes "Welcome to Java File Concept -Reader" to it, and displays this initial content.
2.	It reopens the file in append mode and adds "1234567890" at the end of the existing content.
3.	It reads the file's content (Welcome to Java File Concept -Reader1234567890) and displays it.
4.	The file is deleted using file.delete().
5.	It tries to read the file again, but this throws an exception since the file no longer exists.




## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:

```
try
{
    Writer w1=new FileWriter("testout.txt",true);
    w1.append("1234567890");
    w1.close();
    System.out.println("Append the character in the File Successfully");

}
catch(Exception e)
{
    System.out.println(e);
}
```

## OUTPUT:
```
Expected                                                    	Got
Before Appending :Welcome to Java File Concept -Reader    Before Appending :Welcome to Java File Concept -Reader
Append the character in the File Successfully             Append the character in the File Successfully
Welcome to Java File Concept -Reader1234567890            Welcome to Java File Concept -Reader1234567890
java.io.IOException: Stream Closed                        java.io.IOException: Stream Closed
```

## RESULT:
Thus, the java program to append a NUMBER in a file “testout.txt” using Writer.was executed and verified successfully



