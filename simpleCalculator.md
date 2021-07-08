package com.javatutorials;
import java.util.*;
public class simpleCalculator {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);

        System.out.println("Enter first number :  "); //Asking user for input
        int num1=scanner.nextInt();

        System.out.println("Enter second number: "); //Asking user for input
        int num2=scanner.nextInt();

        scanner.nextLine(); //The java system error i.e. The system usually passes the next line after the nextInt.
                            //Thus to pass only nextLine, not to pass the line, the user will input.
                            //Thus, we have to ask nextLine.

        System.out.println("Enter operator: "); //asking for input , i.e. The user have to choose one operator('+'or '-' or '*' or '/' or '%'
        String operator=scanner.nextLine();

        int result; //Declaring for result

        if (operator.equals("+")) {
            result=num1+num2;
            System.out.println("The result is  "+result );
        }
        else if (operator.equals("-")) {
            result = num1 - num2;
            System.out.println("The result is  " + result);
        }
        else if (operator.equals("*")) {
            result = num1 * num2;
            System.out.println("The result is  " + result);
        }
        else if (operator.equals("/")) {
            result = num1 / num2;
            System.out.println("The result is  " + result);
        }
        else if (operator.equals("%")) {
            result = num1 % num2;
            System.out.println("The result is  " + result);
        }
    }
}




