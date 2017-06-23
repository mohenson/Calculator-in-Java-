# Calculator-in-Java-
Trying to make a calculator type program that can be used to do basic and complex multiplications 
import java.util.Scanner;
 
class Numbers
{
   public static void main(String args[])
   {
      int x, y, z,choice,z2,z3,z4;
       Scanner scan = new Scanner(System.in);
      System.out.println("1. Addition 2.Multiplication 3. Subtraction 4. Division ");
      
  
      choice = scan.nextInt();
      x = scan.nextInt();
      y = scan.nextInt();
     
     
      z = x + y;
      z2 = x * y;
      z3 = x - y;
      z4 = x / y;
      System.out.println("Sum of entered numbers = "+z);
      System.out.println("Product of entered numbers = "+z2);
      System.out.println("Difference of entered numbers = "+z3);
      System.out.println("Quotient of entered numbers = "+z4);
      
      if (choice == 1) System.out.print (""+ z)); 
   }
}
