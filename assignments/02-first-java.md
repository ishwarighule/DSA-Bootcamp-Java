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
3. Write a program to input principle, time, and rate (P, T, R) from the user and
find Simple Interest.
4. Take in two numbers and an operator (+, -, *, /) and calculate the value.
(Use if conditions)
5. Take 2 numbers as input and print the largest number.
6. Input currency in rupees and output in USD.

