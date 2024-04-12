import java.util.Scanner;

//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {
        int peso;
        double altura;
        System.out.println("Digite Peso seguido de Altura:");
        Scanner teclado = new Scanner(System.in);
        peso = teclado.nextInt();
        altura = teclado.nextDouble();
        double imc = peso / (altura * altura);
        System.out.printf("IMC: %.2f\n", imc);
        if (imc < 18.5) {
            System.out.println("Baixo peso");
        } else if (imc > 18.5 && imc < 24.9) {
            System.out.println("Peso adequado");
        } else if (imc >= 25 && imc < 30) {
            System.out.println("Sobrepeso");
        } else if (imc >=30 && imc < 34.9) {
            System.out.println("Obesidade grau 1");
        } else if (imc >=35 && imc <= 40) {
            System.out.println("Obesidade grau 2");
        } else if (imc>40) {
            System.out.println("Obesidade extrema");
            
        }
    }
}
