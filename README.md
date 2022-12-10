# Programacao-de-Solucoes-Computacionais-Ex04-Lista05
import java.util.Scanner;

public class Ex04 {
    public static void main(String[] args) throws Exception {
        System.out.println("Informe um número: ");
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        System.out.println(pOrN(a));
        sc.close();
    }

    public static String pOrN(int a) {
        String resposta;
        if (a <= 0) {
            resposta = "Negativo";
        } else {
            resposta = "Positivo";
        }
        return resposta;
    }
}
