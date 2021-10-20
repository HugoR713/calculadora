# Calculadora
Fazer operações matemáticas  
código feito no Portugol.





programa
{
	
	funcao inicio()
	{
		real soma, div, mult, sub, tabuada
		real n1, n2
		real op
		real resultado, contador, limite
	
		escreva("Qual operação matemática gostaria de resolver? " + "\n")
		escreva("1 Somar \n")
		escreva("2 Subtrair \n")
		escreva("3 Dividir \n")
		escreva("4 Multiplicar \n")
		escreva("Digite o numero indicado: \n ")
		leia(op)
	
		limpa()
		escreva("informe o 1º valor: ")
		leia(n1)
		escreva("informe o 2º valor: ")
		leia(n2)


​		
		se(op == 1){
			soma = n1+n2
			escreva("resultado: " + soma + "\n")
		}senao se(op == 2){
			sub = n1-n2
			escreva("Resultado: " + sub + "\n")
		}senao se(op == 3){
			div = n1 / n2
			escreva("Resultado: " + div +"\n")
		}senao se(op == 4){
			mult = n1 * n2
			escreva("Resultado: " + mult + "\n")
		}senao{
			escreva("Escolha uma das opões listadas. \n")
		}
	}
}
