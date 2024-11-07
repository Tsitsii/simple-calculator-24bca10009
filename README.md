
A simple calculator using switch case.
## Aim:##

-Program to make a simple calculator having basic mathematical operation.

## Objective:##

1.To give a better user experience.
2.Understanding the usage switch case in C Language.
#include <stdio.h>
int main() {
char op;
double first, second;
printf("Enter an operator (+, -, *, /): ");
scanf("%c", &op);
printf("Enter two operands: ");
scanf("%lf %lf", &first, &second);
switch (op) {
case '+':
printf("%.1lf + %.1lf = %.1lf", first, second, first + second);
break;
case '-':
printf("%.1lf - %.1lf = %.1lf", first, second, first - second);
break;
case '*':
printf("%.1lf * %.1lf = %.1lf", first, second, first * second);
break;
case '/':
printf("%.1lf / %.1lf = %.1lf", first, second, first / second);
break;
default:
printf("Error! operator is not correct");
}
return 0;
}
