# exercicio-ac2
calculo da média
public static void main(String[] args) {
     Scanner ler= new Scanner(System.in);
        int ra;
        double n1, n2, n3, m;
        int i, cont = 0;
        for (i = 0; i < 10; i++);
        cont++;
        System.out.printf("Digite o RA do aluno, se nao houver digite 0  ");
         ra = ler.nextInt();
         System.out.printf("Digite a primeira nota  ");
         n1 = nextDouble();
          System.out.printf("Digite a segunda nota  ");
         n2 = nextDouble();
          System.out.printf("Digite a terceira nota  ");
         n3 = nextDouble();

         m = (n1+n2+n3)/3;

         if (m>6) {
         System.out.printf("Voce foi reprovado  " + m);
         }

         else if (m>6 && m < 8) {
             System.out.printf("Voce esta de recuperacao  " + m);
         }

         else {
            System.out.printf("Voce esta aprovado  ");
         }
    }

private static double nextDouble() {

    return 0;
}

}

https://lucid.app/lucidchart/f540f47c-ea46-4137-ac28-16d5e5447009/edit?viewport_loc=-575%2C-385%2C2560%2C1176%2C0_0&invitationId=inv_3d28da6b-b743-46cd-8248-8c90f8a2c072
