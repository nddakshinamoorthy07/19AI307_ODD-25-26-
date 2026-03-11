# Ex. No:2(E) ACCESS MODIFIERS

## QUESTION:

<img width="1005" height="40" alt="image" src="https://github.com/user-attachments/assets/1c8d88c2-0334-4234-9dec-be2496cce258" />

<img width="246" height="136" alt="image" src="https://github.com/user-attachments/assets/0c756112-bfe6-4ad0-bcc5-fde33bad1545" />


## AIM:

To write a Java program to Create a class College with a final variable universityName = "Saveetha University" and  Create objects and print the name.

## ALGORITHM :
1. Start the program and define a College class with a final variable universityName.

2. Assign the value "Saveetha University" to the final variable.

3. In the main method, create an object c1 of the College class.

4. Access the universityName using the object.

5. Display the university name and stop the program.





## PROGRAM:
 ```
Program to implement a Access Modifiers using Java
Developed by: DAKSHINA MOORTHY N D
RegisterNumber:  212224230049
```

## SOURCE CODE:

```java
import java.util.Scanner;
class College 
{
    final String universityName = "Saveetha University";
}

public class prog 
{
    public static void main(String[] args) 
    {
        College c1 = new College();
        System.out.println(c1.universityName);
    }
}
```





## OUTPUT:

<img width="507" height="136" alt="image" src="https://github.com/user-attachments/assets/27eb7fae-382a-496a-a843-c1b450ba4878" />

## RESULT:


Thus, the Java program to Create a class College with a final variable universityName = "Saveetha University" and  Create objects and print the name has been executed successfully.
