# java_ile_faktoriyel

package faktoriyelll;

import java.util.Scanner;

public class Fact {

	public static void main(String[] args) {

		Scanner oku = new Scanner(System.in);
		System.out.println("Bir sayi giriniz: ");
		int sayi = oku.nextInt();
		
		int carpim = 1;
		
		for (int i = 1; i<sayi+1; i++) {
			carpim = carpim * i ;
			System.out.println(i + " Adım " + i + " * " + carpim + " = " + (carpim));
			
		}
		System.out.println("\n\n" + sayi + " sayisinin faktoriyeli = " + carpim);
		

	}

}
