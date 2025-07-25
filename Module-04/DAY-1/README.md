V# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object and “sb” is pointing to that object i.e. the address of the StringBuilder object is stored in reference variable sb.

## ALGORITHM :
1. Initialize a Scanner object to take user input.
2. Read a line of text from the user and store it in variable str1.
3. Create a StringBuilder object sb and initialize it with str1.
4. Calculate the length of the string using sb.length().
5. Display the string length.
6. Calculate the capacity using the formula: sb.length() + 16.
7. Display the calculated capacity.
8. Close the Scanner.

## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: PERARASU M
RegisterNumber: 212222100033
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringBuilderExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String str1 = scanner.nextLine();

        StringBuilder sb = new StringBuilder(str1);

        System.out.println(sb.length());
        System.out.println( (sb.length() + 16));
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/5b7a8739-b88f-465d-a187-a0c1f6e35103)

## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.
