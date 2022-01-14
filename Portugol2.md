programa
{
	
	funcao inicio()
	{
		real n1,n2,n3,n4,m
		cadeia aluno

		escreva("Digite o seu nome: ")
		leia(aluno)
		escreva("Digite as vendas de Janeiro: ")
		leia(n1)
		escreva("Digite as vendas de Fevereiro: ")
		leia(n2)
		escreva("Digite as vendas de Março: ")
		leia(n3)
		escreva("Digite as vendas de Abril: ")
		leia(n4)

		m = (n1+n2+n3+n4)/4

		escreva(aluno + ", a sua média de vendas está em " + m + " reais mensais")
			se(m>=5000)
				escreva("\n" + "Passou!")
			senao
				escreva("\n" + "Reprovou")
		
	}
}
