package com.javatutorials;

import java.util.Scanner;

public class evenOrOddOrZero {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in); //Creating a scanner

        System.out.println("Enter a number"); //Asking input to user
        int num=scanner.nextInt(); //For the space that is needed for inputing from user

        /**
         * if the number that is input by user is divisible by 2 i.e. it is left by zero.
         * it is even number.
         * if the number that is input by user is not divisible i.e. the remainder,except zero is left
         * the number is odd number.
         * if it is zero
         * it is zero.
         * After deciding, the program will return ouput to user.(even or odd or zero)
         */

        if (num==0) {
            System.out.println("It is zero: ");
        }

        else if (num%2==0) {
            System.out.println("It is even number:  ");
        }

        else {
            System.out.println("It is odd number: ");
        }
    }
}

