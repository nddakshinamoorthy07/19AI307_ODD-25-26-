# Ex. No:2(C) ACCESS SPECIFIERS

## QUESTION:

<img width="1196" height="95" alt="image" src="https://github.com/user-attachments/assets/3551d2d7-80ac-4d43-b6ff-130e7ef08789" />


## AIM:

To write a Java program to create a class called Employee with private instance variables employee_id, employee_name, and employee_salary. Provide public getter and setter methods to access and modify the id and name variables, but provide a getter method for the salary variable that returns a formatted string.



## ALGORITHM :
1. tart the program and define an Employee class with private variables employee_id, employee_name, and employee_salary.

2. Create getter and setter methods to access and modify the employee details.

3. In the main method, create a Scanner object and an Employee object (e1).

4. Read the employee ID, name, and salary from the user and store them using setter methods.

5. Display the employee details including the formatted salary and stop the program.





## PROGRAM:
 ```
Program to implement a Access Specifiers using Java
Developed by: DAKSHINA MOORTHY N D
RegisterNumber:  212224230049
```

## SOURCE CODE:


```java
import java.util.Scanner;
public class Employee 
{
    
    private int employee_id;
    private String employee_name;
    private double employee_salary;

    
    public int getEmployeeId() 
    {
        return employee_id;
    }
    public void setEmployeeId(int employee_id) 
    {
        this.employee_id = employee_id;
    }

    
    public String getEmployeeName() 
    {
        return employee_name;
    }
    public void setEmployeeName(String employee_name) 
    {
        this.employee_name = employee_name;
    }

  
    public void setEmployeeSalary(double employee_salary) 
    {
        this.employee_salary = employee_salary;
    }

   
    public String getFormattedSalary() 
    {
        return String.format("₹%.2f", employee_salary);
    }

    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        Employee e1 = new Employee();
        e1.setEmployeeId(sc.nextInt());
        sc.nextLine();
        e1.setEmployeeName(sc.nextLine());
        e1.setEmployeeSalary(sc.nextDouble());
        System.out.println("Employee 1");
        System.out.println("ID: " + e1.getEmployeeId());
        System.out.println("Name: " + e1.getEmployeeName());
        System.out.println("Salary: " + e1.getFormattedSalary());
        
        
    }

}

```




## OUTPUT:

<img width="735" height="439" alt="image" src="https://github.com/user-attachments/assets/676d2f87-0e30-4d34-b6a5-9f031d0cde88" />


## RESULT:


Thus, the Java program to create a class called Employee with private instance variables employee_id, employee_name, and employee_salary. Provide public getter and setter methods to access and modify the id and name variables, but provide a getter method for the salary variable that returns a formatted string has been executed successfully.
