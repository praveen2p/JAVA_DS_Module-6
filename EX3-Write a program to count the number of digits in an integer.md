# EX3 Write a program to count the number of digits in an integer.
## DATE:
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
```
1. Start
2. Read an integer n
3. Define a recursive function countDigits(n)
   If n == 0, return 0
   Else, return 1 + countDigits(n / 10)
4. If the number is 0, print 1 (since it has one digit)
5. Otherwise, call countDigits(n) and display the result
6. End
```   

## Program:
```
/*
Program to to count the number of digits in an integer
Developed by: PRAVEEN K
RegisterNumber: 212223040152
 import java.util.Scanner;

public class Main {
    static int countDigits(int n) {
        if (n == 0)
            return 0;
        return 1 + countDigits(n / 10);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        if (n == 0)
            System.out.println(1);
        else
            System.out.println(countDigits(Math.abs(n)));
        sc.close();
    }
}
*/
```

## Output:

<img width="402" height="364" alt="image" src="https://github.com/user-attachments/assets/c9294783-6e8f-46d3-94ce-14312e898d38" />


## Result:
Thus, the Java program to to count the number of digits in an integer is implemented successfully.
