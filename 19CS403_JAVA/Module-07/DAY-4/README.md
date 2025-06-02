# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:

```
class Display
{
    static synchronized void wish(String name)
    {
        for(int i=0;i<=1;i++)
        {
            System.out.print("Welcome :: ");
            try
            {
                Thread.sleep(600);
            }
            catch(InterruptedException e)
            {
                
            }
            System.out.println(name);
        }
    }



}
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/1fc76157-3a36-4650-92a6-6f4f6599fb4c)


## RESULT:
Thus the java program for synchronization was executed successfully.

