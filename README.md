#include <stdio.h>

int main() {
    int a, b, temp;

    // Input two numbers
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    // Display the numbers before swapping
    printf("Before swapping: a = %d, b = %d\n", a, b);

    // Swap the numbers using a temporary variable
    temp = a;
    a = b;
    b = temp;

    // Display the numbers after swapping
    printf("After swapping: a = %d, b = %d\n", a, b);

    return 0;
}
