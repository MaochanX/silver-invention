# silver-invention
#include<stdio.h>

//Binary Inverse by Rachif//
int main() {

    int num, rem;
    printf("\nEnter a number :");
    scanf("%d", &num);

    while(num!=0) {
        rem=num%2;
        printf("%d", rem);
        num=num/2;

    }
    return 0;
    
}
