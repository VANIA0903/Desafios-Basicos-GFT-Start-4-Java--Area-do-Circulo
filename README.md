# Desafios-Basicos-GFT-Start-4-Java--Area-do-Circulo
import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		Locale.setDefault(Locale.US);
		
		Scanner sc = new Scanner(System.in);
		
		/*
		 * Fa�a um programa para ler o valor do raio de um circulo, e depois mostrar o
		 * valor da area deste circulo com quatro casas decimais conforme exemplos.
		 * F�rmula da �rea: area = pi . raio2 Considere o valor de pi = 3.14159
		 */
		
		
		System.out.println("-- EXERCICIO 1 --");
		System.out.println("-- CALCULAR �REA DO C�RCULO --");

		double pi, A, r;
		
		pi = 3.14159;
		
		System.out.println("Informe o raio do circulo: ");
		r = sc.nextDouble();
		
		A = pi * Math.pow(r, 2.0);
		
		System.out.printf("A �rea do ciruclo �: %.4f%n", A);
		
		sc.close();
		
	}
