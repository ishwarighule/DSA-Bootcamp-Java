# [Video Link](https://youtu.be/TAtrPoaJ7gc)

## Write Java programs for the following:

1. Write a program to print whether a number is even or odd, also take input.

    import java.io.*;
    import java.util.Scanner;

    public class Main
    {
           public static void main(String[] args) {
           int num;
           System.out.println("Enter a number");
        
          Scanner input = new Scanner(System.in);
        
          num = input.nextInt();
        
         if(num%2==0){
            System.out.println("Number is even");
          }
         else{
             System.out.println("Number is odd");
           }
        
         }
    }


2. Take name as input and print a greeting message for that name.

import java.io.*;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        String name;
        System.out.println("Enter your name");
        
        Scanner input = new Scanner(System.in);
        
        name = input.nextLine();
         System.out.println("Hey! "+ name);
    }
}


3. Write a program to input principle, time, and rate (P, T, R) from the user and find Simple Interest.

import java.io.*;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        double p,t,r;
        System.out.println("Enter principle, time and rate ");
        
        Scanner input = new Scanner(System.in);
        
        p = input.nextDouble();
        t = input.nextDouble();
        r = input.nextDouble();
        
        double simpInt = (p*t*r) / 100;
        
         System.out.println("Simple Intrest is "+ simpInt);
    }
}



4. Take in two numbers and an operator (+, -, *, /) and calculate the value.(Use if conditions)

import java.io.*;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        double a,b;
        System.out.println("Enter 2 numbers ");
        
        Scanner input = new Scanner(System.in);
        
        a = input.nextDouble();
        b = input.nextDouble();
   
         System.out.println("Enter operator");
         String op = input.next();
         
         double result= 0;
         
         if(op.equals("+")){
             result= a+b;
             System.out.println("Result is " + result);
         }
          else if(op.equals("-")){
             result= a-b;
             System.out.println("Result is " + result);
         }
         
         else if(op.equals("/")){
             result= a/b;
             System.out.println("Result is " + result);
         }
         
         else if(op.equals("*")){
             result= a*b;
             System.out.println("Result is " + result);
         }
         
         else if(op.equals("%")){
             result= a%b;
             System.out.println("Result is " + result);
         }
         
         else{
             System.out.println("Invalid operator");
         }
    }
}



5. Take 2 numbers as input and print the largest number.

import java.io.*;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        int a,b;
        System.out.println("Enter 2 numbers ");
        
        Scanner input = new Scanner(System.in);
        
        a = input.nextInt();
        b = input.nextInt();
        
        if (a>=b){
             System.out.println( a + " is greater than" +b);
        } 
        else if(a==b){
            System.out.println( a + " is equal to" +b);
        }
        
        else{
            System.out.println( b + " is greater than" +a);
        }
        }
}




6. Input currency in rupees and output in USD.

import java.io.*;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        double inr,b,usd;
        System.out.println("Enter amount in Rupees' ");
        
        Scanner input = new Scanner(System.in);
        
        inr = input.nextDouble();
        
        usd = inr/75.06;
        
        System.out.println("Amount in USD: " + usd);
        
        }
}


7. To calculate Fibonacci Series up to n numbers.
8. To find out whether the given String is Palindrome or not.
9. To find Armstrong Number between two given number.
