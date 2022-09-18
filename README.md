# FIBONACCI-SERIES
FINONACC SERIES


// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int n1=0, n2=1, no, n3, i;
    printf("ENTER THE NUMBERS\n");
    scanf("%d", &no);
    for(i=2; i<no; i++)
    {
        n3=n1+n2;
        printf("%d\n", n3);
        n1=n2;
        n2=n3;
    }
    return 0;
}
