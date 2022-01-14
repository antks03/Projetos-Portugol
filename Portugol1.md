programa
{
	
	funcao inicio()
	{
		cadeia nome[] ={"Antonio","Matheus","Amanda"}
		real altura[] ={1.67,1.76,1.65}
		escreva("------------ \n")
		escreva("Tabela \n")
		escreva("------------ \n\n")
		escreva("Nome:  ", "\t\t"  ,"Altura:","\n")

		para (inteiro posicao = 0; posicao <= 2; posicao++)
		{
			escreva(nome[posicao], "\t\t" ,altura[posicao],"m", "\n")
		}
	}

}
