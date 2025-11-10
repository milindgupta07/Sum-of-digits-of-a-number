# Sum-of-digits-of-a-number
Using C language program is made which gives the output of sum of digits of a numbers
#include <stdio.h>
int main() {
    int num, sum = 0;
    scanf("%d", &num);
    while(num > 0) {
        sum += num % 10;
        num /= 10;
    }
    printf("%d", sum);
    return 0;
}
