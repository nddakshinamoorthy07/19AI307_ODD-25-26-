# Ex. No:2(A) CLASS AND OBJECT

## QUESTION:

<img width="1019" height="215" alt="image" src="https://github.com/user-attachments/assets/60826a64-2e48-4898-a5a9-17aff2c1e9fb" />


## AIM:

To write a java program to create a class Student with attributes name, rollNumber, marks and to create 3 student objects and print their details.



## ALGORITHM :
1. Start the program and define a Student class with variables name, rollNumber, and marks.

2. Create a Scanner object to read input from the user.

3. Create three Student objects (s1, s2, s3) and read their name, roll number, and marks from the user.

4. Store the entered values in the respective student objects.

5. Display the details of all three students and stop the program.





## PROGRAM:
 ```
Program to implement a Class and Objects using Java
Developed by: DAKSHINA MOORTHY N D
RegisterNumber:  212224230049
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class Main 
{
    static class Student
    {
        String name;
        int rollNumber;
        int marks;
    }
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);

        Student s1 = new Student();
        s1.name = sc.next();
        s1.rollNumber = sc.nextInt();
        s1.marks = sc.nextInt();

        Student s2 = new Student();
        s2.name = sc.next();
        s2.rollNumber = sc.nextInt();
        s2.marks = sc.nextInt();

        Student s3 = new Student();
        s3.name = sc.next();
        s3.rollNumber = sc.nextInt();
        s3.marks = sc.nextInt();

        System.out.println(s1.name + " | " + s1.rollNumber + " | " + s1.marks);
        System.out.println(s2.name + " | " + s2.rollNumber + " | " + s2.marks);
        System.out.println(s3.name + " | " + s3.rollNumber + " | " + s3.marks);

        sc.close();
    }
}

```





## OUTPUT:

<img width="617" height="291" alt="image" src="https://github.com/user-attachments/assets/ae39aa0f-9b4a-476e-92e9-7bf29aa54e49" />


## RESULT:


Thus, the java program to create a class Student with attributes name, rollNumber, marks and to create 3 student objects and print their details has been completed successfully.
