
public class Main {
    public static void main(String[] args) {
        double[] precos = {1.50, 2.75, 5.00, 3.25};
        double soma = 0;

        for (int i = 0; i < 4; i++) {
            soma = soma + precos[i];
        }

        System.out.println(soma);
    }
}


public class Main {
    public static void main(String[] args) {
        int[] notas = {85, 92, 78, 95, 88};

        for (int i = 0; i < 5; i++) {[frutascom.txt](https://github.com/user-attachments/files/22374481/frutascom.txt)

            System.out.println("Nota " + (i + 1) + ": " + notas[i]);
        }
    }
}

public class Main {
    public static void main(String[] args) {
        String[] frutas = {"Maçã", "Banana", "Laranja", "Uva"};

        System.out.println(frutas[0]);

        frutas[1] = "Morango";

        System.out.println(frutas[1]);
    }
}

public class Main {
    public static void main(String[] args) {
        
        int[] numeros = {10, 20, 30, 40, 50};

        System.out.println("Valor na terceira posição (índice 2): " + numeros[2]);
    }
}

public class Main {
    public static void main(String[] args) {
        boolean[] status = {true, false, true};

        if (status[0]) {
            System.out.println("O primeiro status está ativo.");
        } else {
            System.out.println("O primeiro status está inativo.");
        }
    }
}
