# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation and right shift for 60 integer number with 2 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 60 and 2.
3.	Use left shift operator (<<) and shift the value of it two times.
4.	Use right shift operator (>>) and shift the value of it two times.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main(){
    int a,b,c;
    scanf("%d",&a);
    b=a>>2;
    c=a<<2;
    printf("After Left Shift Operation value of a is:%d\n",c);
    printf("After Right Shift Operation value of a is:%d",b);
    return 0;
}
```
<img width="973" height="538" alt="image" src="https://github.com/user-attachments/assets/726ecc2e-f842-4bd2-b6e4-a16f8e010494" />


## OUTPUT
<img width="1052" height="331" alt="image" src="https://github.com/user-attachments/assets/02b0d765-2c1b-43ee-9324-95504b9eac96" />









## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
    if(a==b){
        printf("Numbers are Equal");
    }
    else{
        printf("Numbers are not Equal");
    }
    return 0;
}
```
<img width="1024" height="582" alt="image" src="https://github.com/user-attachments/assets/afac6efa-56b0-4d3b-9ab5-f44e81500817" />

## OUTPUT
<img width="715" height="349" alt="image" src="https://github.com/user-attachments/assets/0bf193a9-3605-4eb5-a908-99b29e209043" />
         
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main(){
    char str[20];
    scanf("%s",str);
    for(int i=0;str[i]!='\0';i++){
        str[i]=str[i]+32;
    }
    printf("Lower case String is:%s",str);
    return 0;
}
```
<img width="727" height="606" alt="image" src="https://github.com/user-attachments/assets/6578123c-60df-49d6-872f-d18a555f9ff3" />

## OUTPUT
<img width="817" height="301" alt="image" src="https://github.com/user-attachments/assets/735ef7f8-2704-4927-87e3-ee8fd75e07b4" />




## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main(){
    char str[100];
    int i=0,words=1;
    scanf("%[^\n]s",str);
    do{
        if(str[i]==' '){
            words++;
        }
        i++;
    }while(str[i]!='\0');
    printf("%d\n",words);
    return 0;
}
```
<img width="971" height="678" alt="image" src="https://github.com/user-attachments/assets/116698bb-1e97-41c7-8526-7a2ee9b0b235" />

## OUTPUT
<img width="572" height="299" alt="image" src="https://github.com/user-attachments/assets/3967a542-60d9-4a45-adb5-2203dcbbf6dc" />





## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM


## OUTPUT
 

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

