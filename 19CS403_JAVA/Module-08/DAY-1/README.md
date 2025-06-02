# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to append a String "SAVEETHA ENGINEERING COLLEGE" in a file "sample.txt" using OutputStream.

## ALGORITHM :
1.  Define the string str as "SAVEETHA ENGINEERING COLLEGE" and convert it into a byte array b using getBytes().
2.	Open the file sample.txt using FileOutputStream with the append flag set to true to enable appending.
3. Write the entire byte array b to the file.
4.	Close the output stream.
5.	Open the file sample.txt using FileInputStream.
6. Read the contents of the file byte-by-byte, convert each byte to a character, and display the file's content.

7.Close the input stream.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Surendhar K
RegisterNumber:  212222040166
*/
```

## Sourcecode.java:
```
 try
   {
      FileOutputStream f=new FileOutputStream("sample.txt",true);
      String s="SAVEETHA ENGINEERING COLLEGE";
      byte b[]=s.getBytes();
      f.write(b);
      f.close();
      System.out.println("Successfully Completed");
   }
      catch(Exception e){
           System.out.println(e);
   }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/7f90dae3-b88e-4649-8548-d062775a89cb)


## RESULT:
Thus, the implementation of a Java Program to append a String "SAVEETHA ENGINEERING COLLEGE" in a file "sample.txt" using OutputStream was executed and verified successfully.

