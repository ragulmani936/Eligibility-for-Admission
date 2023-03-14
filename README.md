# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
### STEP 1
Declare variables for maths, physics, chemistry, and totalMarks.
### STEP 2
Use the Console.ReadLine() to get the inputs from the user.
### STEP 3
Calculate totalMarks as per the elegibility is mentioned.
### STEP 4
Check whether the student is eligible for admission using if else condition wth the given eligibility criteria.
### STEP 5
Use the Console.WriteLine() to display the eligibility status of the student.

## Program:
~~~
NAME : RAGUL M
REG NO: 212221230080
~~~
~~~
using System;
class EligibilityforAdmission
{
    static void Main()
    {
        int m, p, c,t1,t2;
        string name;
        Console.WriteLine("Enter the student name");
        name = Console.ReadLine();
        Console.WriteLine("Enter the maths marks");
        m = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the physics marks");
        p = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the chemistry marks");
        c = Convert.ToInt32(Console.ReadLine());
        t1 = m + p + c;
        t2 = m + p;
            if(m>=65 && p>=55 && c>=50)
        {
            if(t1>=180 || t2>=140)
            {
                Console.WriteLine(name + "is eligible for engineering admission");
            }
            else
            {
                Console.WriteLine(name + "not eligible for engineering admission");
            }
        }
    }
}
~~~


## Output:
![output]()


## Result:
Thus, C# program to find the eligibility for admission to an engineering course has been executed successfully.
