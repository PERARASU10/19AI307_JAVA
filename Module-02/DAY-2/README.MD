# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display the addition number using private modifiers only.

## ALGORITHM :
1.	Start the program.
2.	Define a class named `addition`
3.	Declare two private integer variables, `num1` and `num2`
4.	Define a private method `add()` that:
a)	Returns the sum of `num1` and `num2`
5.	Define a public method `display(int n1, int n2)` that:
a)	Assigns `n1` to `num1` and `n2` to `num2`
b)	Calls the `add()` method and prints the result using `System.out.println`
6.	Define the `main` method as static
a)	Create an instance of the `addition` class called `ad`
b)	Call the `display(8, 9)` method on the `ad` object
7.	End

## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: PERARASU M
RegisterNumber: 212222100033
*/
```

## Sourcecode.java:
```
class A
{ 
    public void display() 
    { 
        int a=8,b=9;
        System.out.println(a+b); 
    }
}
public class Main{
    public static void main(String args[])
    {
        A obj = new A();
        obj.display();
    }
}
```

## OUTPUT:

![Screenshot 2025-04-30 141557](https://github.com/user-attachments/assets/834be99a-0747-40ce-ac6c-345dfaa49ef7)

## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.
