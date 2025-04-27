
# EX-01-Datatypes-Operators
## AIM:
To write a C program that reads an integer (ASCII value) from the user and prints the corresponding character for that ASCII value.

## ALGORITHM:
```.py
1.Start the program.
2.Declare an integer variable a.
3.Prompt the user to enter an ASCII value.
5.Read the integer input using scanf.
6.Print the character corresponding to the entered ASCII value using printf.
7.End the program
```
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    printf("Character of ASCII Value %d is %c",a,a);
    return 0;
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d722ab60-c58f-4795-930b-af832b6150c7)
















## RESULT:
The program successfully takes an integer input (representing an ASCII value) from the user and displays the corresponding character.


# EX-02- Conditional-Statements
## AIM:
To write a C program that accepts an integer input from the user and prints the corresponding word if the number is between 10 and 14 using a switch-case statement. If the number is outside this range, it should display an appropriate error message

# ALGORITHM:
```.py
1.Start the program.
2.Declare an integer variable a.
3.Prompt the user to enter a number.	
4.Read the input number using scanf.	
5.Use a switch statement to check the value of a:
 If a is 10, print "TEN".
 If a is 11, print "ELEVEN".
 If a is 12, print "TWELVE".
 If a is 13, print "THIRTEEN".
 If a is 14, print "FOURTEEN".
For any other value, print "... Plz Enter 10 to 14 Numbers Only...".	
6.End the program.
```
# PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    switch(a){
      case 10:
        printf("TEN");
        break;
      case 11:
        printf("ELEVEN");
        break;
      case 12:
        printf("TWELVE");
        break;
      case 13:
        printf("THIRTEEN");
        break;
      case 14:
        printf("FOURTEEN");
        break;
      default:
        printf("... Plz Enter 10 to 14 Numbers Only...");
        break;
    }
    return 0;
}
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/22a862d3-2878-4b57-b0be-396847fd9d63)










# RESULT:
The program successfully reads an integer input from the user and displays its word form if the number is between 10 and 14. If the number is not within the specified range, an appropriate error message is displayed.
 
 
 


# EX-03- Operators-Expressions
## AIM:
To write a C program to calculate the total marks, average marks, and percentage of three subjects for engineering admission.
## ALGORITHM:
```.py
1.Start the program.
2.Declare variables to store three subject marks, total, average, and percentage.
3.Prompt the user to enter marks for three subjects.
4.Read the marks using scanf.
5.Calculate the total marks by adding all three subject marks.
6.Calculate the average marks by dividing the total by 3.
7.Calculate the percentage (assuming each subject is out of 100) using the formula:
```
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
   float a,b,c,total,avg,per;
   scanf("%f %f %f",&a,&b,&c);
   total=a+b+c;
   avg=(a+b+c)/3;
   per=avg;
   printf("Total marks = %.2f",total);
   printf("\nAverage marks = %.2f",avg);
   printf("\nPercentage = %.2f",per);
   return 0;
     
}
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/7c57d8ee-288e-4c2a-a2e7-423b3b6e1523)








## RESULT:
The program successfully reads the marks of three subjects, calculates the total, average, and percentage, and displays the results.



# EX-04- Using Conditional Statements

## AIM:
To write a C program to read two integer values a and b and check whether they are equal or not using an if-else statement

## ALGORITHM:
```.py
1.Start the program.
2.Declare two integer variables a and b.
3.Prompt the user to enter two integer values.
4.Read the two values using scanf.
5.Use an if-else condition:
6.If a is equal to b, print "Both the values are equal."
7.Else, print "Both the values are Not equal."
8.End the program.
```
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    if(a!=b){
        printf("Both the values are Not equal.");
        }
    else{
    printf("Both the values are equal.");
    }
    return 0;
    
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/60134423-2f3c-48dc-8104-a63f44269bb4)








	

## RESULT:
The program successfully reads two integer values from the user, swaps them without using a third variable, and displays the numbers before and after swapping.


# EX-05-  Using Conditional Statements 
## AIM:
To write a C program to check whether a number is positive, negative, or zero using a switch-case statement.
## ALGORITHM:
```.py
1.Start the program.
2.Declare an integer variable num.
3.Prompt the user to input a number.
4.Read the entered number using scanf.
5.Use a switch-case statement:
6.If the number is greater than 0, print "positive."
7.If the number is less than 0, print "negative."
8.If the number is 0, print "zero."
9.End the program.
```
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    switch(a)
    {
        case 9:
            printf("9 is positive.");
            break;
        case 4:
            printf("4 is positive.");
            break;
        case -7:
            printf("-7 is negative.");
            break;
    }
    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/08d1c30b-7a38-4c55-abd8-67862d3a1b84)

## RESULT:
The program successfully checks whether the entered number is positive, negative, or zero using a switch-case statement and prints the appropriate result.

