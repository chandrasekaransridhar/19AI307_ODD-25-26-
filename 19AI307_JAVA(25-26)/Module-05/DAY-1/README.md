# Ex.No:5(A) INPUTSTREAMREADER

## QUESTION:

Write a program to read user input from the keyboard using **InputStreamReader**.

### Example

| **Input** | **Result**    |
| --------- | ------------- |
| Manoj     | Hello, Manoj! |

## AIM:

To write a Java program that reads a string input from the keyboard using `InputStreamReader` and displays a greeting message.

## ALGORITHM :

1. Start the program.
2. Import the necessary packages `java.util` and `java.io`.
3. Create an `InputStreamReader` object to read user input.
4. Wrap it in a `BufferedReader` to read a line of text.
5. Read the user's name and print a greeting.
6. End the program.

## PROGRAM:

```
/*
Program to implement a InputStreamReader using Java
Developed by: Antony Aswin Kumar L
RegisterNumber:  212225040024
*/
```

## SOURCE CODE:

```java
import java.util.*;
import java.io.*;

class prog {
    public static void main(String args[]) throws IOException {
        Scanner sc = new Scanner(System.in);
        InputStreamReader isr = new InputStreamReader(System.in);
        BufferedReader br = new BufferedReader(isr);
        String name = br.readLine();
        System.out.println("Hello, " + name + "!");
    }
}
```

## OUTPUT:

<img width="581" height="323" alt="image" src="https://github.com/user-attachments/assets/53a498a7-bb85-4619-8f5e-25b66a3b64b1" />


## RESULT:

Thus, the Java program using `InputStreamReader` to read user input was successfully executed.
