# programa-cervejas
package aluno;

import java.util.Scanner;


public class Cervejas {
	public static void main (String[] args) {
		
		int	cerveja = 99;
		Scanner ler = new Scanner(System.in);
		int aceita = 0;
		int quantidade = 0;
		
		while( cerveja > 0) {
			System.out.println(" Agora são: " + cerveja + " e passo para frente");
			cerveja = cerveja - 1;
			
			
			if ( cerveja == 0 ) {
				System.out.println("Você quer colocar mais cervejas 1-sim e 2-não?:");
				aceita = ler.nextInt();
			
			if ( aceita == 1) {
				System.out.println("Quantas cervejas?");
				cerveja = ler.nextInt();
						
			}else {
				System.out.println("Acabou! Só amanhã");
			}
			}
		
		
		
		
		}
		
		ler.close();
		
	}

}
