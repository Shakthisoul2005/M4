# EX-16-LEFT-SHIFT-OPERATION
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
```
1.Start
2.Declare two character arrays (str1 and str2)
3.Read both strings from the user
4.Loop through each character of both strings
5.Compare characters and check for end of string
6.Print whether strings are equal or not and stop
```
## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main()
{
    char a[100],b[100];
    scanf("%s %s",a,b);
    if(strcmp(a,b)==0)
    {
        printf("strings are same");
    
    }
    else
    {
        printf("strings are not same");
    }
}
```
## OUTPUT

![Screenshot 2025-04-29 183713](https://github.com/user-attachments/assets/63db196d-dec0-41ea-84dc-ff9eb681f228)








## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

C Program to print  numbers  range from M to N (including M and N values) divisible by 3 in reverse order..

## ALGORITHM
```
1.Start
2.Declare variables M and N
3.Read values of M and N
4.Loop from N to M in reverse
5.Check if the number is divisible by 3
6.Print the number if it is, then stop
```
📄 C Program:
## PROGRAM
```
#include<stdio.h>
int main()
{
    int M,N;
    
    scanf("%d%d",&M,&N);
    for(int i=N; i>=M;i--){
        if(i%3==0){
            printf("%d ",i);
        }
    }
 
    return 0;
}
```

## OUTPUT
           ![Screenshot 2025-04-29 183928](https://github.com/user-attachments/assets/cbf9b7f6-ecb1-404c-913c-015cff24af0f)

## RESULT

Thus the program has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C program to perform the basic left and right shift operation for 22 integer number. 

## ALGORITHM
```
1.Start
2.Declare an integer variable and assign value 22
3.Perform left shift (<<) and right shift (>>)
4.Store the results in separate variables
5.Print the original number and shifted results
6.Stop
```


## PROGRAM
```
#include<stdio.h>
int main()
{
    int a = 22;
    printf("After Left Shift Operation value of a is:%d\n",a<<2);
    printf("After Right Shift Operation value of a is:%d\n",a>>2);
}
```
## OUTPUT
![Screenshot 2025-04-29 184240](https://github.com/user-attachments/assets/bb8f93bd-98e4-41b3-9267-253277843da1)




## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a program in C to read any Month Number in integer and display Month name in the word using Switch Case?
## ALGORITHM
```
1.Start
2.Declare an integer variable to store the month number
3.Read the month number from the user
4.Use a switch-case to check the month number
5.Display the corresponding month name
6.Stop
```
## PROGRAM
```
#include<stdio.h>
int main()
{
    int month;
    scanf("%d",&month);
    switch(month)
    {
        case 1:
        printf("January\n");
        break;
        case 2:
        printf("february");
        break;
        case 3:
        printf("march");
        break;
        case 4:
        printf("april");
        break;
        case 5:
        printf("May");
        break;
        case 6:
        printf("June");
        break;
        case 7:
        printf("July");
        break;
        default:
        printf("invalid");
        break;
    }
}
```

## OUTPUT


![Screenshot 2025-04-29 184531](https://github.com/user-attachments/assets/5f517656-50ad-4d91-87ce-206b26964431)



## RESULT
Thus the program has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a c program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using for loop.
## ALGORITHM
```
1.Start
2.Declare two strings: source and destination
3.Copy the string character by character using a for loop
4.Count words in the string by detecting spaces
5.Print the copied string and the word count
6.Stop
```
## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main()
{
    char s1[100],s2[100],b[100];
    int i,length=0;
    scanf("%[^\n]s",s1);
    strcpy(s2,s1);
    printf("s2:%s",b);
    for(i=0;s1[i]!='\0';i++)
    {
        length++;
    }
    printf("%s\nTotal words=%d",s1,length);
}
```

## OUTPUT
 
![Screenshot 2025-04-29 184736](https://github.com/user-attachments/assets/8dc1b6da-eebc-4966-a8d5-655a1caf142d)

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

