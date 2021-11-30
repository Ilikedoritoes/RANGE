
#include <stdlib.h>
#include <stdio.h> 
#define _CRT_SECRURE_NO_WARNINGS

//      index++ -> index+1
//      index+=2   -> index+2

int main()
{
    int limit;
    int index;
    int num;
    printf("please write 2 numbers.\n");
    scanf_s("%d %d\n", &num, &limit); 

    for (index=num;index<limit;index+=1)
    {
        printf(" -> %d", num);
    }

}
 

[range-of-numbers.zip](https://github.com/Ilikedoritoes/RANGE/files/7617027/range-of-numbers.zip)
