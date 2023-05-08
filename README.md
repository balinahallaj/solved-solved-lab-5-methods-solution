Download Link: https://assignmentchef.com/product/solved-solved-lab-5-methods-solution
<br>
Lab 5 â€“ Introduction to Methods

We want to find the average of three numbers (doubles). Consider the following class (which is not complete):

“`java// Program finds the minimum of 3 numbersimport java.util.Scanner;

public class Lab5{// find the minimum of three numberspublic static void main(String[] args){Scanner input = new Scanner(System.in);double one; // first numberdouble two; // second numberdouble three; // third numberSystem.out.printf(“%s
 %s
 %s
”, “Type the end-of-file indicator to terminate”, “On UNIX/Linux/Mac OS X type System.out.print(“Or enter first number: “);

while (input.hasNext()){one = input.nextDouble();// Write code to get the remainder of the inputs and// convert them to double values */// Write code to display the minimum of the three// floating-point numbers */System.out.printf(“
%s
 %s
 %s
”, “Type the end-of-file indicator to terminate”, “On UNIX/Linux/Mac OS X type System.out.print(“Or enter first number: “);} // end while

} // end main// determine the smallest of three numbers// write the header for the minimum3 method

public static{// determine the minimum valuereturn // Write code to compute the minimum of three numbers} // end method minimum3}“`

1. Add the appropriate code in the while loop to input the remainder of the input data.2. Complete the header of the minimum3 method.3. Write the code that returns the smallest value.4. The code shown has two printf statements that are large and repetitive. Create a new method, promptUser, that will accomplish the same task.5. Create a new method, findMinimum, that returns the smallest of two doubles.6. Rewrite the minimum3 method use the findMinimum.