package olamundo;
import java.util.Scanner;

public class Calculadora {

	public static void main(String[] args) {

	  Scanner scan = new Scanner (System.in);
	  
	  int num1, num2, resultado;
	  int operacao;
		
	    System.out.println("Digita 1 para soma");
	    System.out.println("Digita 2 para subtrair");
	    System.out.println("Digita 3 para multiplicar");
	    System.out.println("Digita 4 para dividir");

        operacao = scan.nextInt();


        System.out.println("Digite o primeiro numero:");
        num1 = scan.nextInt(); 
        System.out.println("Digite o segundo numero:");
        num2 = scan.nextInt();

        
        switch(operacao){
        case 1: resultado = num1 + num2;
        System.out.println("A soma é:" +resultado);
        break;
        case 2: resultado = num1 - num2;
        System.out.println("A subtração é:" +resultado);
        break;
        case 3: resultado = num1 * num2;
        System.out.println("A multiplicação é" +resultado);
        break;
        case 4: resultado = num1 / num2;
        System.out.println("A divisão é:" +resultado);
        break;
        }    
	}   
	}
