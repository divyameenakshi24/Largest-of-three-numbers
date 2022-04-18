# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```
using System;
public class divya
{
    public static void Main()
    {
        int num1, num2, num3;
        Console.WriteLine("Find the largest of three numbers:\n");

        Console.WriteLine("Enter the 1st number :");
        num1 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the  2nd number :");
        num2 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the 3rd  number :");
        num3 = Convert.ToInt32(Console.ReadLine());

        if (num1 > num2)
        {
            if (num1 > num3)
            {
                Console.WriteLine("The 1st Number is the greatest among three.");
            }
            else
            {
                Console.WriteLine("The 3rd Number is the greatest among three.");
            }
        }
        else if (num2 > num3)
            Console.WriteLine("The 2nd Number is the greatest among three.");
        else
            Console.WriteLine("The 3rd Number is the greatest among three.");
    }
}
```

## Output:
![Screenshot 2022-04-18 185724](https://user-images.githubusercontent.com/75235402/163819026-567759e3-ceb0-453f-a2d5-5463a27c3494.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
