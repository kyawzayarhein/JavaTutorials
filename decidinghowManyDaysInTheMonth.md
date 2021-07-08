package com.javatutorials;

import java.util.Scanner;

public class decidinghowManyDaysInTheMonth {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);

        System.out.println("Enter a month: "); //Asking for input
        String month=scanner.nextLine();

        /**
         * Recall
         * September, April, June and November have 30 days.
         * february has 28 days.
         * Others have 31 days
         * We have to use " || ", that is called "Or"
         * because if we don't use it, we have to write many program sentences and so we have to use it.
         */

        if (month.equals("September")||month.equals("April")
                ||month.equals("June")||month.equals("November")) {
            System.out.println("The month "+month+" have 30 days: ");
        }

        else if (month.equals("January")||month.equals("March")||
                month.equals("May")||month.equals("July")||
                month.equals("August")||month.equals("December")||
                month.equals("October")) {
            System.out.println("The month "+month+" have 31 days:");
        }
        
        else if(month.equals("February")) {
            System.out.println("The month "+month+" have 28 days:");
        }
    }
}
