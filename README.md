import java.util.Scanner;

public class idades {

public static void main(String[] args){

     Scanner teclado = new Scanner(System.in);
     
     int idade;
     
     System.out.print("coloque a sua idade aqui");
     idade = teclado.nextInt();
     
     if (idade >=121) System.out.print(" você bateu o record da pessoa mais velha do mundo, meus PARABENS ");
     
     else if (idade>0 && idade <=11) System.out.print(" você é uma criança " );
     
     else if (idade>11 && idade <=17) System.out.print(" você é um adolecente ");
     
     else if (idade>17 && idade <=59) System.out.print(" você é um adulto ");
     
     else if (idade>60 && idade <=120) System.out.print(" você é um idoso ");
     
     else if (idade<=0 ) System.out.print(" essa idade está invalida ");
     
     
    }
}
