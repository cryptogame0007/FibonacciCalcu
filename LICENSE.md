
public class FibonacciCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите номер числа Фибоначчи: ");
        int n = scanner.nextInt();

        int fibonacciNumber = calculateFibonacci(n);
