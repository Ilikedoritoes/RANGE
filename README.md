
#define _CRT_SECRURE_NO_WARNINGS
#include <stdlib.h>
#include <stdio.h> 
#define _CRT_SECRURE_NO_WARNINGS


//      index++ -> index+1
//      index+=2   -> index+2

// יש לכתוב תוכנית אשר מדפיסה את המספרים הזוגים בלבד מ0 עד 100.
int main()
{
    int limit;
    int num;
    printf("please write 2 numbers.\n");
    scanf("%d %d\n", &num, &limit); //<----------- לשים &?

    for (num;limit;num++)
    {
        printf(" -> %d", num);

    }


}

// FOR (מה הערך בהתחלה ; מה הגבול של הערך ; בכה להכפיל ולהגדיל אותו)
// נא לכתוב תרגיל שקולט מהמשתמש 2 מספרים שלמים ו מדפיס את כול המספרים בתווח של אותם המספרים שהמשתמש הכניס.
// לדוגמא:
// 1 7 
 // 7 ידפיס 1 2 3 4 5 6  

[range-of-numbers.zip](https://github.com/Ilikedoritoes/RANGE/files/7617027/range-of-numbers.zip)
