# FibonacciCalcu
FibonacciCalcu
import java.util.Scanner;

public class FibonacciCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите номер числа Фибоначчи: ");
        int n = scanner.nextInt();

        int fibonacciNumber = calculateFibonacci(n);
        System.out.println("Число Фибоначчи под номером " + n + ": " + fibonacciNumber);
    }

    public static int calculateFibonacci(int n) {
        if (n <= 1) {
            return n;
        }
        return calculateFibonacci(n - 1) + calculateFibonacci(n - 2);
    }
}
