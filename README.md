nclude <stdio.h>

int main() {
    printf("Name: Jerico B. Salac\n");
    printf("ID Number: 2025304114\n\n");

    int num1 = 10, num2 = 20;
    int sum, difference, product;
    float quotient;

    sum = num1 + num2;
    difference = num1 - num2;
    product = num1 * num2;
    quotient = (float)num1 / num2;

    printf("=== Basic Arithmetic Operations ===\n");
    printf("The sum of %d and %d is %d\n", num1, num2, sum);
    printf("The difference of %d and %d is %d\n", num1, num2, difference);
    printf("The product of %d and %d is %d\n", num1, num2, product);
    printf("The quotient of %d and %d is %.2f\n", num1, num2, quotient);

    return 0;
}
