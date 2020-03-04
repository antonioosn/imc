# imc
----------------------------------------------------------
        real peso, altura, imc, pesoMin, pesoMax
		escreva("Digite o seu peso: ")
		leia(peso)
		escreva("Digite a sua altura: ")
		leia(altura)
		
		imc = (peso)/(altura*altura)
		escreva("Seu imc é: ", imc, "\n")
		
	se(imc<=15){escreva("Extremamente abaixo do peso")}
	se(imc>15 e imc<=16) {escreva(" Você está gravemente abaixo do peso")}
	se(imc>16 e imc<=18.5){escreva("Você está abaixo do peso ideal")}
	se(imc>18.6 e imc<=25){escreva("Você está no peso Ideal")}
	se(imc>25.1 e imc<=30){escreva("Você está com Sobrepeso")}
	se(imc>30.1 e imc<=35){escreva("Você está com obesidade Grau 1")}
	se(imc>35.1 e imc<=40){escreva("Você está com obesidade Grau 2(grave)")}
	se(imc>40){escreva("Você está com obesidade Grau 3 (Mórbida)")}

	pesoMin = (18.5 * altura * altura)
	pesoMax = (25 * altura * altura)
	escreva("\n" ,"Seu peso ideal deve ser entre:", pesoMin)
	escreva(" e " , pesoMax)	
