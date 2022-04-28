# day-of-the-week-challlenge
A java program to print the day of the week challenge using if else  or switch statements.
import java.util.Scanner;

public class dayoftheweekchallenge{
   public static void main(String[] args) {
    Scanner in = new Scanner(System.in);
    int num = in.nextInt();
    switch(num){
        case 0: 
            System.out.println("The day is Sunday.");
            break;
        case 1: 
            System.out.println("The day is Monday.");
            break;
        case 2: 
            System.out.println("The day is Tuesday.");
            break;
        case 3:  
            System.out.println("The day is  Wednesday.");
            break;
        case 4: 
            System.out.println("The day is Thursday.");
            break;
        case 5: 
            System.out.println("The day is Friday.");
            break;
        case 6: 
            System.out.println("The day is Saturday.");
            break;
        default :
            System.out.println("Please enter a valid number.");
            break;
        }
    in.close();

    }
}

    
