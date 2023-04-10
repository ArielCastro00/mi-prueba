package com.jps;

import java.util.Scanner;

public class Calculadora {
		Scanner dato = new Scanner(System.in);
		public double sumar(double valor1, double valor2)
		{
			double resultado = 0;
			resultado = valor1 + valor2;
			return resultado;
		}
		
		public double restar(double valor1, double valor2)
		{
			double resultado = 0;
			resultado = valor1 - valor2;
			return resultado;
		}
		
		public double multiplicar(double valor1, double valor2)
		{
			double resultado = 0;
			resultado = valor1 * valor2;
			return resultado;
		}
		
		public double dividir(double valor1, double valor2)
		{
			double resultado = 0;
			resultado = valor1 / valor2;
			return resultado;
		}

		public void calculo ()
		{
			double resultado, valor1, valor2;
			System.out.println("Elija la opcion que quiera realizar:");
			System.out.println("1/Sumar");
			System.out.println("2/Restar");
			System.out.println("3/Multiplicar");
			System.out.println("4/Dividir");
			int opcion = dato.nextInt();
			switch (opcion)
			{
			case 1:
				System.out.println("Ingrese el primer valor:");
				valor1 = dato.nextDouble();
				System.out.println("Ingrese el segundo valor:");
				valor2 = dato.nextDouble();
				resultado=sumar(valor1, valor2);
				System.out.println("La suma es: " + resultado);
				break;
			case 2:
				System.out.println("Ingrese el primer valor:");
				valor1 = dato.nextDouble();
				System.out.println("Ingrese el segundo valor:");
				valor2 = dato.nextDouble();
				resultado=restar(valor1, valor2);
				System.out.println("La resta es: " + resultado);
				break;
			case 3:
				System.out.println("Ingrese el primer valor:");
				valor1 = dato.nextDouble();
				System.out.println("Ingrese el segundo valor:");
				valor2 = dato.nextDouble();
				resultado=multiplicar(valor1, valor2);
				System.out.println("La multiplicacion es: " + resultado);
				break;
			case 4:
				System.out.println("Ingrese el primer valor:");
				valor1 = dato.nextDouble();
				System.out.println("Ingrese el segundo valor:");
				valor2 = dato.nextDouble();
				resultado=dividir(valor1, valor2);
				System.out.println("La division es: " + resultado);
				break;
			default: System.out.println("Error");
			}
		}
		public static void main (String []args)
		{
			Calculadora cp= new Calculadora();
			cp.calculo();
		}
}
