# Ex. No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:

<img width="795" height="191" alt="image" src="https://github.com/user-attachments/assets/6b7ab3ac-8e0a-4eae-bbd1-7cc4ac74282e" />

## AIM:

To write a java program to create a class that uses a constructor to initialize variables and overrides toString() method.



## ALGORITHM :
1. Start the program and define a Student class with variables name and age.

2. Create a parameterized constructor to initialize the name and age of the student.

3. Override the toString() method to return the student details in a formatted string.

4. In the main method, read the student name and age from the user and create a Student object.

5. Display the student details using the object and stop the program.





## PROGRAM:
 ```
Program to implement a Variable scope and Constructor using Java
Developed by: DAKSHINA MOORTHY N D
RegisterNumber: 212224230049
```

## SOURCE CODE:

```java
import java.util.Scanner;
class Student
{
    String name;
    int age;
    
    Student(String name,int age)
    {
        this.name = name;
        this.age = age;
    }
    public String toString()
    {
        return "Student{name='"+name+"', age="+age+"}";
    }
}
public class main
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();
        int age = sc.nextInt();
        Student s1 = new Student(name,age);
        System.out.println(s1);
        
    }
}
```





## OUTPUT:

<img width="783" height="293" alt="image" src="https://github.com/user-attachments/assets/af1a4f33-0b60-4648-bb48-8dc84f455c27" />

## RESULT:


Thus, the java program to create a class that uses a constructor to initialize variables and overrides toString() method has been executed successfully.
