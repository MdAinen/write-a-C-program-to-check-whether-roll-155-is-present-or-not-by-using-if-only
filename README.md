#include <stdio.h>

int main() {
    int rollNumber;
    printf("Enter a roll number: ");
    scanf("%d", &rollNumber);
    if (rollNumber == 155) {
        printf("Roll number 155 is present.\n");
    } else {
        printf("Roll number 155 is not present.\n");
    }
    return 0;
}
