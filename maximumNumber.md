package com.javatutorials;
import java.util.Scanner;

public class maximumNumber {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);

        System.out.println("Enter first number: ");
        int num1=scanner.nextInt();

        System.out.println("Enter second number: ");
        int num2=scanner.nextInt();

        System.out.println("Enter third number: ");
        int num3=scanner.nextInt();

        int max;

        if (num1>num2) {
            if (num1 > num3) {
                max = num1;
            } else {
                max = num3;
            }

        } else {
            if (num2 > num3) {
                    max = num2;
                  }
                else {
                    max = num3;
                }
            }
                    System.out.println("Maximum is  "+max);
    }
}
