# lekhs
#include <stdio.h>

int main() {
    double num1, num2;

    // Ask user for input
    printf("Enter two numbers: ");
    scanf("%lf %lf", &num1, &num2);

    // Compare the numbers and print the result
    if (num1 > num2) {
        printf("%.2lf is the largest.\n", num1);
    } else if (num2 > num1) {
        printf("%.2lf is the largest.\n", num2);
    } else {
        printf("Both numbers are equal.\n");
    }

    return 0;
}
