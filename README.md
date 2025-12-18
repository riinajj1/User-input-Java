import java.util.Scanner;

public class App {
    public static void main(String[] args) throws Exception {

        Scanner in = new Scanner(System.in);
        String input;
        String input1;

        System.out.println("First number?");
        input = in.nextLine();

        System.out.println("Second number?");
        input1 = in.nextLine();

        int num1 = Integer.parseInt(input);
        int num2 = Integer.parseInt(input1);

        int result = num1 + num2;
        System.out.println(input + " + " + input1 + " = " + result);
    }
}
