# Ex5 Count Inversions in an Array
## DATE:
## AIM:
To write a Java program  to Count the number of inversions in an array where inversion is defined as: arr[i] > arr[j] and i < j

## Algorithm
```
1. Start
2. Read the number of elements n
3. Read n elements into array arr
4. Initialize count = 0
5. For each pair (i, j) such that i < j
    If arr[i] > arr[j], increment count by 1
6. Display count as the total number of inversions
7. End

```   

## Program:
```
/*
Program toto Count the number of inversions in an array where inversion is defined as: arr[i] > arr[j] and i < j
Developed by: PRAVEEN K
RegisterNumber: 212223040152
 import java.util.Scanner;

public class Main {
    static int countInversions(int[] arr, int n) {
        int count = 0;
        for (int i = 0; i < n - 1; i++)
            for (int j = i + 1; j < n; j++)
                if (arr[i] > arr[j])
                    count++;
        return count;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++)
            arr[i] = sc.nextInt();
        System.out.println(countInversions(arr, n));
        sc.close();
    }
}
*/
```

## Output:

<img width="413" height="249" alt="image" src="https://github.com/user-attachments/assets/bb864f15-a21a-4a7f-96d7-ab6d3e810257" />


## Result:
Thus the Java program to to Count the number of inversions in an array where inversion is defined as: arr[i] > arr[j] and i < jis implemented successfully.
