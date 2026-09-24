# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1.Start.

2.Dedare three variable value of type int for marks.

3.Prompt the user to enter a value.

4.Read the value using scanf
.
5.Find total and average.

6.Print the result

7.End.
## Program:
```
#include <stdio.h>
int main()
{
    float a,b,c,d,e,f;
    float total,average,percentage;
    scanf("%f%f%f%f%f%f",&a,&b,&c,&d,&e,&f);
    total = a+b+c+d+e+f;
    average = (a+b+c+d+e+f)/6.0;
    percentage = (total/600)*100;
    printf("Total marks = %.2f\n",total);
    printf("Average marks = %.2f\n",average);
    printf("Percentage = %.2f\n",percentage);
    return 0;
}
```

## Output:
<img width="1145" height="442" alt="image" src="https://github.com/user-attachments/assets/63ced4bc-c9e6-4d11-ba44-8aeb8de00b6f" />

## Result:
Thus the program was executed and the output was verified successfully.
