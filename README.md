# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
step 1 : Import the 'System' namespace to use the classes present in the 'System' namespace.

step 2: Declare the Main method.

step 3: Declare name variable in string format and marks variable in integer format.

step 4: Using " Console.Write " print the statement and get the input from user using " Console.ReadLine " .

step 5: Add the 3 subject marks and store it in tot1. Add the marks of physics and maths and store it in tot2.

step 6: Using Nested if loop check whether the student is eligible or not eligible for engineering admission with the conditions given.

step 7: print the result

## Program:

 A K MOHAN RAJ
```
using System;

namespace ConsoleApp16
{
    class Program
    {
        static void Main(string[] args)
        {
            int phy, math, chem, total1, total2;
            string name;
            Console.WriteLine("Enter the student name : ");
            name = Console.ReadLine();
            Console.WriteLine("Enter the physics marks : ");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the chemistry mark : ");
            chem = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the Math marks : ");
            math = Convert.ToInt32(Console.ReadLine());
            total1 = math + phy + chem;
            total2 = math + phy;
            if(math>=65 && phy>=55 && chem >= 50)
            {
                if(total1>=180 && total2 >= 140)
                {
                    Console.WriteLine(name + "is eligible for engineering admission");
                }
            }
            else
            {
                Console.WriteLine(name + "is not eligible for engineering admission");
            }
        }
    }
}

```
## Output:
![Screenshot 2023-03-17 162238](https://user-images.githubusercontent.com/94828147/225885555-cbd4858d-a5ac-4892-8483-103c76483b32.png)

## Result:
Thus a C# program to find the eligibility for admission to an engineering course is written and executed.
