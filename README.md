# Java-Day-10-Smallest-of-Two-Numbers
# Java Day 10 - Smallest of Two Numbers

This program takes two numbers from the user and finds the smallest number using `if-else if-else`.

## Example

Input:

```text
25
15
```

Output:

```text
Smallest number = 15
```

## Concepts Used

* Scanner
* User input
* Variables
* `if`
* `else if`
* `else`
* Comparison operators

## How It Works

1. The program creates a `Scanner` object to take input.
2. The user enters two numbers.
3. The program compares both numbers.
4. If the first number is smaller, it displays the first number.
5. If the second number is smaller, it displays the second number.
6. If both numbers are equal, it displays an equal message.

## Java Code

```java
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int num1 = sc.nextInt();

        System.out.print("Enter second number: ");
        int num2 = sc.nextInt();

        if (num1 < num2)
        {
            System.out.println("Smallest number = " + num1);
        }
        else if (num2 < num1)
        {
            System.out.println("Smallest number = " + num2);
        }
        else
        {
            System.out.println("Both numbers are equal.");
        }

        sc.close();
    }
}
```

## Output

```text
Enter first number: 25
Enter second number: 15
Smallest number = 15
```

## Goal

The goal of this project is to practice comparison operators and conditional statements in Java by finding the smallest of two numbers.
