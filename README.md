# AskingMoreQuestions
Input/Output Debugging Assignment
Submit Assignment
Due No Due Date  Points 1  Submitting a website url
This application takes three numbers adds them together and outputs the result, or at least it should, can you fix it?

Create a new Java project in Eclipse and pubish to a new repository on GitHub.

import java.util.Scanner;

public class AskingQuestions 
{ 
  public static void main( String[] args ) 
  { 
    Scanner keyboard = new Scanner(System.in);

    double num1, num2, num3;

    System.out.print( "First integer? " );
    num1 = keyboard.nextString();

    System.out.print( "Second integer? " );
    num2 = keyboard.nextInt();

    System.out.print( "Third integer? " );
    num3 = keyboard.nextDouble();
  }
  System.out.println("The total is : " + (num1 + num2 + num3));
}
