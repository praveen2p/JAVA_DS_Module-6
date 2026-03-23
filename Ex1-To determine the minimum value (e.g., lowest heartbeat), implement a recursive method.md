# EX 1 You’re creating a health monitoring device which stores several sensor readings in an array. To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.
## DATE:
## AIM:
To write a JAVA program To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.

## Algorithm
Step 1: Start

Step 2: Read the number of heartbeats (n) and store them in an array arr.

Step 3: Define a recursive method findMin(arr, n) that returns the minimum value among the first n elements.

Step 4: If n == 1, return arr[0] (base case).
        Otherwise, recursively find the minimum of the first n-1 elements and compare it with arr[n-1].
        Return the smaller value.
        
Step 5: Display the result as the lowest heartbeat.

Step 6: End   

## Program:
```
/*
Program To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.
import java.util.Scanner;

public class Main {
    static int findMin(int arr[], int n) {
        if (n == 1)
            return arr[0];
        int min = findMin(arr, n - 1);
        return Math.min(min, arr[n - 1]);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] heartbeat = new int[n];
        for (int i = 0; i < n; i++) {
            heartbeat[i] = sc.nextInt();
        }
        int minValue = findMin(heartbeat, n);
        System.out.println("The lowest heartbeat value is: " + minValue);
        sc.close();
    }
}

Developed by: PRAVEEN K
RegisterNumber: 212223040152 
*/
```

## Output:

<img width="708" height="429" alt="image" src="https://github.com/user-attachments/assets/50c19d76-3e53-442d-a6ba-d05a6afe7a78" />


## Result:
Thus the JAVA prograM ti find the minimum value (e.g., lowest heartbeat), implement a recursive method has implemented successfully
