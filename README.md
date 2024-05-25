# ch7
import java.util.Scanner;

public class SumOfDigits { public static void main(String[] args) { Scanner scanner = new Scanner(System.in);

    System.out.print("Enter a string: ");
    String input = scanner.nextLine();
    int sum = 0;
    for (int i = 0; i < input.length(); i++) {
        sum += Character.getNumericValue(c);
        
    }
    System.out.println( sum);
}
}
