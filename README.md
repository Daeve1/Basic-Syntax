# Basic-Syntax
public class BasicSyntax {

    public static void main(String[] args) {
        
        String  name = "Dave Cyrel Lavega";
        System.out.println(name);
    }
}
import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a number to find its factorial: ");
        int num = scanner.nextInt();
        int fact = 1;
        for (int i = 1; i <= num; i++) {
            fact *= i;
        }
        System.out.println("Factorial: " + fact);
        scanner.close();
    }
}
