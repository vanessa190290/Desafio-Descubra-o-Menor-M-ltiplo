# Desafio-Descubra-o-Menor-M-ltiplo
 Descubra o Menor Múltiplo
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    int numero = scanner.nextInt();

    int minimoMultiplo = 0;
    if (numero % 2 == 0) {
      minimoMultiplo = numero;
    } else {
      minimoMultiplo = numero * 2;
    }

    System.out.println("O resultado eh:" + minimoMultiplo);
  }

}
