Algoritmo calcular_nivelsalario
	Leer nivel_profesor
	leer salario_actiual
		si nivel_profesor es "profesor adjunto" incremento
		incremento = 3.5/100
				si nivel_profesor es "profesor auxiliar" incrmento
		incremento = 4.1/100
			si nivel_profesor es "profesor asitente" incremento
		incremento = 4.8/100
			si nivel_profesor es "profesor titular" incremento 
		incrmento = 5.3/100
	
	escribir " nivel no valido"
	
	nuevo_salario = salario_actiual + (salario_actiual * incrmento)
	// salida
	Escribir "el nuevo salario del ", nivel_profesor, " es: ", nuevo_salario
		
	
FinAlgoritmo
