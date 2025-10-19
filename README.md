# program-1-d-
C module 1

EX-NO:1)d)- Find whether the given character is a vowel or not.

Date:19/10/2025
Name: VASANTH S
Ref no: 25017538

AIM:
Write a C program to check whether the given character is a vowel or not.

ALGORITHM:
1)Get a character input from the user.
2)Check whether it is vowel or not using if else statement.
3)Print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if((ch>='a' && ch<='z') || (ch>='A' && ch<='Z'))
    {
        if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U')
        printf("Vowel.");
        else
        printf("Consonant.");
    }
}
```
OUTPUT:
<img width="380" height="147" alt="Screenshot 2025-10-19 202740" src="https://github.com/user-attachments/assets/872bd578-881c-440a-9c50-13003790533e" />

RESULT:
Thus the C program to check whether the given character is vowel or not is executed successfully.




