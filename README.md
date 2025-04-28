# SUM-OF-NATURAL-NUMBERS-USING-RECURSION
# AIM:
To write a Java program to find the sum of N natural numbers using recursion.
# ALGORITHM:
1.Start the program.
2.Define a recursive function sumnat(int n).
3.If n == 0, return 0 (base case).
4.Else, return n + sumnat(n-1).
5.In the main method:
6.Declare and initialize the value of n.
7.Call the function sumnat(n) and print the result.
8.End the program.
# PROGRAM:
```
// Program to find sum of N natural numbers using recursion
public class sumofnatusingrec {
    public static int sumnat(int n) {
        if (n == 0) return 0; // base case
        return n + sumnat(n - 1); // recursive call
    }
    public static void main(String[] args) {
        int n = 5; 
        System.out.println("Sum of first " + n + " natural numbers is: " + sumnat(n)); 
    }
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/a2c0e50e-7b31-423e-a1fa-3717f74dc410)

# RESULT:
The Java program to find the sum of N natural numbers using recursion was successfully compiled and executed.

