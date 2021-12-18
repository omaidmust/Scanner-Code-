




/**
 *
 * @author omaidmustafa
 * 
 * 12/13/21
 */

import java.util.Scanner;

public class Main {
    public static void main(String[] argrs)
{

    Scanner sc = new Scanner(System.in); //Scanner
    
    System.out.println("Tell me your first name.");
    String name =sc.next();
    
    System.out.println("Tell me your first age.");
    int age =sc.nextInt();
    
    System.out.println("Tell me a quote you like.");
    String quote =sc.next();
    quote += sc.nextLine();
    
    System.out.println("Thank you " + name + " you are "+ age +" years old.");
    System.out.println("The quote you liked was " + quote);
    
}
    
}
