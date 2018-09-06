# Saves
import java.util.*;

public class Exercicio {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        // verificar se e par ou impar, c_a
        int numero = scanner.nextInt();
        int inteiro = numero % 2;

        System.out.println("Par: "+(inteiro==0));
        
    }
}
