# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Alluguri Srikrishna Teja
RegisterNumber: 212222040006
*/
```

## Sourcecode.java:

```
import java.util.*;  
public class Ex {  
   public static void main(String args[]){  
  

   TreeMap<String,String> tree_map1=new TreeMap<String,String>();      
  
 
   Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      String n1 = sc.next();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    
  System.out.println(tree_map1);
        if(tree_map1.containsKey("C1")){
            System.out.println("The Tree Map contains key C1");
        } else {
            System.out.println("The Tree Map does not contain key C1");
        }
        if(tree_map1.containsKey("C5")){
            System.out.println("The Tree Map contains key C5");
        } else {
            System.out.println("The TreeMap does not contain key C5");
        }
    }
}

```

## OUTPUT:
```
Input                 	Result
3               {C1=Red, C2=Green, C5=Blue}
C1              The Tree Map contains key C1
Red             The Tree Map contains key C5
C2
Green
C5
Blue
```
## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
