
### calculadora simple con do while

```psc
Algoritmo calculadoraSimpleConDoWhile
	imprimir "=====calculadora simple======"
	definir continuar Como Caracter
	
	repetir 
		escribir "ingrese el primer numero"
		leer n1
		escribir "ingrese segundo numero"
		leer n2
		
		escribir "ingrese una operacion: +,-,*,/"
		leer op
		
		segun op HACER
			"+":
				imprimir "resultado:" , ConvertirATexto(n1+n2)
			"-":
				imprimir "resultado:" , ConvertirATexto(n1+n2)
			"*":
				imprimir "resultado:" , ConvertirATexto(n1+n2)
			"/":
				imprimir "resultado:" , ConvertirATexto(n1+n2)
				
		fin segun
		imprimir "desea continuar" 
	leer continuar
	Hasta Que continuar== "no"
	
	
FinAlgoritmo
```
