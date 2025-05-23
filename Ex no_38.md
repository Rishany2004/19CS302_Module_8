### Task

### Given a positive integer denoting , do the following:

# If  41<=n <=49 print the lowercase English word corresponding to the number (e.g., forty one for 41 , forty two for 42 etc.).
If n>49 print Greater than 49.
## Input Format

The first line contains a single integer, .

## Constraints

## Output Format

If  41<=n <=49 print the lowercase English word corresponding to the number (e.g., forty one for 4 , forty two for 42 etc.).
If n>49 print Greater than 49.
## Sample Input

41
## Sample Output

forty one
### AIM:
To determine a positive integer denoting , do the following: If 41<=n <=49 print the lowercase English word corresponding to the number (e.g., forty one for 41 , forty two for 42 etc.).

### ALGORITHM:
Start
Input an integer n.
Check if n is between 41 and 49 (i.e., 41 <= n <= 49).
If true, print the corresponding English word for the number.
If n is greater than 49, print "Greater than 49."
Use a series of conditional statements (if-else) to handle the different possible values of n within the given range (41-49).
Terminate the program after displaying the appropriate message.
End.
### PROGRAM:
```
#include <stdio.h>
int main() {
    int n;
    scanf("%d", &n);
    if (n >= 41 && n <= 49) {
        switch(n) {
            case 41: printf("forty one\n"); break;
            case 42: printf("forty two\n"); break;
            case 43: printf("forty three\n"); break;
            case 44: printf("forty four\n"); break;
            case 45: printf("forty five\n"); break;
            case 46: printf("forty six\n"); break;
            case 47: printf("forty seven\n"); break;
            case 48: printf("forty eight\n"); break;
            case 49: printf("forty nine\n"); break;
        }
    } else if (n > 49) {
        printf("Greater than 49\n");
    }
    return 0;

}
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/a97d5b52-7810-4f5e-a4ec-a8f096475658)


### RESULT:
Thus, the program is executed and verified successfully.
