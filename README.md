# EX-4-B-UNCONDITIONAL-STATEMENTS
## AIM :
Write a C program to check whether profit or loss using simple if statement
## ALGORITHAM :
1.Start

2.Declare variables to store the cost price (costPrice) and the selling price (sellingPrice).

3.Prompt the user to enter the cost price and read it into the costPrice variable.

4.Prompt the user to enter the selling price and read it into the sellingPrice variable.

5.Calculate the profit or loss using the formula: profitLoss = sellingPrice - costPrice.

6.Use an if statement to check if there's a profit or a loss:

7.End.
## PROGARM :
```
#include<stdio.h>
int main(){
int a,b;
scanf("%d%d",&a,&b);
if(a<b){
printf("Profit!!");
}
if(b<a)
{
printf("Loss!!");
}
return 0;
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-4-B-UNCONDITIONAL-STATEMENTS/assets/121418437/fb78b240-4263-44b4-b3c1-a7e2c0a963b7)

## RESULT :
Thus , The C program has been executed successfully.

# EX-4-C-STRINGS
## AIM :
To find the length of the string 'LAPTOP'
## ALGORITHAM :
1.Start

2.Initialize a variable length to 0 to store the length of the string.

3.Loop through each character of the string 'LAPTOP':

4.The value of length now represents the length of the string 'LAPTOP'.

5.End
## PROGARM :
```
#include<stdio.h>
#include<string.h>
int main()
{
char a[100];
int i;
scanf("%s",a);
for(i=0;a[i]!='\0';i++);
printf("Length of Str is %d",i);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-4-B-UNCONDITIONAL-STATEMENTS/assets/121418437/5d38e5de-66f8-4871-8556-be136639b639)

## RESULT :
Thus , The C program has been executed successfully.

# EX-4-D-STRINGS APPLICATIONS
## AIM :
Write a C program to count the total number of words in a given string using do While
loop.
## ALGORITHAM :
1.Start

2.Declare variables to store the input string (inputStr), a variable to store the word count (wordCount), and an index variable (i).

3.Prompt the user to enter a string and read it into the inputStr variable.

4.Initialize wordCount to 0 and i to 0.

5.Use a do-while loop to iterate through the string until the end of the string is reached:

a. Inside the loop, check if the current character (inputStr[i]) is a space (' ') or the null character ('\0').

b. If it is, increment the wordCount by 1, indicating the start of a new word.

c. Increment i to move to the next character in the string.

d. Repeat the loop until the end of the string is reached.

6.Print the word count (wordCount).

7.End.
## PROGARM :
```
# include <stdio.h>
# include <string.h>
int main(){
char a[100];
scanf("%[^\n]s",a);
int i,count=0;
for(i=0;a[i]!='\0';i++) {
if (a[i+1]==' ' ||
a[i+1]=='\0'){count++;
}
}
printf("%d",count);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-4-B-UNCONDITIONAL-STATEMENTS/assets/121418437/8e39a288-4905-4788-a7f7-9e09da1d7ff4)

## RESULT :
Thus , The C program has been executed successfully.
