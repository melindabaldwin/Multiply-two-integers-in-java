# Multiply-two-integers-in-java
Multiply two integers in java
import java.util.Scanner;
 
public class NhanHaiSo {
 
     public static void main(String[] args) {
 
         /* requires the user to enter the first and second numbers from the keyboard
          */
         Scanner scan = new Scanner(System.in);
         System.out.print("enter first number: ");
 
         int num1 = scan.nextInt();
 
         System.out.print("Enter second number: ");
         int num2 = scan.nextInt();
 
         // Perform the product of two numbers.
         int tich = num1*num2;
 
         // display the result on the screen
         System.out.println("Result: "+tich);
     }
}
