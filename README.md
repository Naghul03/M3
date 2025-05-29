# EX-11-EMI-CALCULATOR

## AIM

To write a program to prepare EMI calculator using function without return type and with arguments.

## ALGORITHM

1.	Start the program.
2.	Read principal amount, rate of interest and months.
3.	Pass these values as arguments to function.
4.	Calculate EMI using the formula, amt=(prpow(1+r,t))/(pow(1+r,t)-1)
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include<stdio.h>
#include<math.h>
double calculateEMI(double p,double r,int t){
r=r/100/12;
return (p*r*pow(1+r,t))/(pow(1+r,t)-1);
}
int main(){
double p,r,emi;
int t;
scanf("%lf%lf%d",&p,&r,&t);
emi=calculateEMI(p,r,t);
printf("EMI: %.2lf\n",emi);
return 0;
}

```

## OUTPUT


![image](https://github.com/user-attachments/assets/8eef3a7f-51a7-432a-9100-1c9d6e3074d4)


## RESULT

Thus the program to prepare EMI calculator using function without return type with arguments has been executed successfully
 
 


# EX-12-FIBONACCI-SERIES
## AIM
To write a C program to generate the Fibonacci series for the value 6.

## ALGORITHM
1.	Start the program.
2.	Read number of terms to display.
3.	Add the previous two terms and store it in new term.
4.	Assign 2nd term to 1st term and 3rd term to 2nd term.
5.	Repeat steps 3 and 4 n number of times.
6.	Display the result.
7.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main(){
int n,a=0,b=1,c,i;
scanf("%d",&n);
printf("%d %d ",a,b);
for(i=3;i<=n;i++){
c=a+b;
printf("%d ",c);
a=b;
b=c;
}
return 0;
}

```
## OUTPUT


![image](https://github.com/user-attachments/assets/b06266f1-591f-4cd5-8a66-48ba5949a271)


## RESULT
Thus the program to generate the Fibonacci series for the value 6 has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY
## AIM
To write a C program to read n elements as input and print the last element of the array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	Print the last element.
5.	Stop the program.

## PROGRAM

```
#include<stdio.h>
int main(){
int n,i;
scanf("%d",&n);
int a[n];
for(i=0;i<n;i++)scanf("%d",&a[i]);
printf("%d",a[n-1]);
return 0;
}

```
## OUTPUT


![image](https://github.com/user-attachments/assets/05ff1cf0-64c6-4c9b-8b2b-a841e7ce76bb)




## RESULT
Thus the program to read n elements as input and print the last element of the array has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS
## AIM
To write a C Program to count total number of positive elements in an array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	If the array value can be divided by 2 then increment count by 1.
5.	Display result.
6.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main(){
int n,i,x,count=0;
scanf("%d",&n);
for(i=0;i<n;i++){
scanf("%d",&x);
if(x%2==0)count++;
}
printf("%d",count);
return 0;
}

```
## OUTPUT


![image](https://github.com/user-attachments/assets/d5660f3f-5c89-4091-b05f-8b6413be35e9)


## RESULT
Thus the program to count total number of positive elements in an array has been executed successfully.





 
 


# EX -15 - Replace All Even Elements With 'E' In One Dimensional Array

## Aim:
To write a C program to replace all even elements with 'E' in one dimensional array

## Algorithm:
1.	Input the array:
  Read the size of the array.
  Input the elements of the array.
2.	Iterate through the array:
 	For each element of the array, check if the element is even (i.e., if the element modulo 2 equals 0).
3.	Replace even elements with 'E':
     If an element is even, replace that element with the character 'E'.
4.	Output the updated array:
 Print the updated array after replacements.

## Program:
```
#include<stdio.h>
int main(){
int n,i;
scanf("%d",&n);
int a[n];
for(i=0;i<n;i++)scanf("%d",&a[i]);
for(i=0;i<n;i++){
if(a[i]%2==0)printf("E ");
else printf("%d ",a[i]);
}
return 0;
}

```
## Output:
 
![image](https://github.com/user-attachments/assets/e9f396ee-ba85-49b4-8179-035d4ad7590d)


## Result:

Thus, the program to replace all even elements with 'E' in one dimensional array was verified successfully.



