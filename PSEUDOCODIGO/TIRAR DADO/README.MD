 ## NUMERO AL AZAR, TIRAR DADO

````psc
Algoritmo tirar_Dados
	definir dice1,dice2 Como Entero
	Para contador=1 Hasta 10 Con Paso 1 Hacer
		dice1 = aleatorio(1,6)
		dice2 = aleatorio(1,6)
		si dice1 = dice2 Entonces
			imprimir  dice1," ",dice2 "the dice are the same"   
	
		sino 
			imprimir dice1," ",dice2
		FinSi
	Fin Para
	
	
FinAlgoritmo  
````
