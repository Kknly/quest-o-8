# question-8

import java.util.Scanner;

public class CalculadoraCircunferencia {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite o raio da circunferência: ");
        double raio = scanner.nextDouble();
        
        double area = Math.PI * Math.pow(raio, 2);
        double comprimento = 2 * Math.PI * raio;
        
        System.out.println("A área da circunferência é: " + area);
        System.out.println("O comprimento da circunferência é: " + comprimento);
        
        scanner.close();
    }
}
