# javaoperators.txt

import java.util.Scanner;

/**
 *
 * @author 1BSCCSA42
 */
public class Operators {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);

        
        System.out.print("Enter first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter second number: ");
        int num2 = scanner.nextInt();

        
        System.out.println("\nArithmetic Operations:");
        System.out.println("Addition: " + (num1 + num2));
        System.out.println("Subtraction: " + (num1 - num2));
        System.out.println("Multiplication: " + (num1 * num2));
        System.out.println("Division: " + (num1 / num2));
        System.out.println("Modulus: " + (num1 % num2));

        
        System.out.print("\nEnter first boolean value (true/false): ");
        boolean bool1 = scanner.nextBoolean();

        System.out.print("Enter second boolean value (true/false): ");
        boolean bool2 = scanner.nextBoolean();

       
        System.out.println("\nRelational Operations:");
        System.out.println("Is num1 equal to num2? " + (num1 == num2));
        System.out.println("Is num1 not equal to num2? " + (num1 != num2));
        System.out.println("Is num1 greater than num2? " + (num1 > num2));
        System.out.println("Is num1 less than num2? " + (num1 < num2));
        System.out.println("Is num1 greater than or equal to num2? " + (num1 >= num2));
        System.out.println("Is num1 less than or equal to num2? " + (num1 <= num2));

       
        System.out.println("\nLogical Operations:");
        System.out.println("Logical AND (bool1 && bool2): " + (bool1 && bool2));
        System.out.println("Logical OR (bool1 || bool2): " + (bool1 || bool2));
        System.out.println("Logical NOT (!bool1): " + (!bool1));

       
        System.out.print("\nEnter a number for ternary operation: ");
        int ternaryNum = scanner.nextInt();

        String result = (ternaryNum % 2 == 0) ? "Even" : "Odd";
        System.out.println("\nTernary Operation:");
        System.out.println("The number " + ternaryNum + " is " + result);

      
        scanner.close();
    }
}
    
    

