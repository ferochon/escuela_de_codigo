### ESTOS EJERCICIOS REALIZALOS EN PSEINT PARA QUE PUEDAS PRACTICAR EL PENSAMIENTO COMPUTACIONAL.

Escribe un programa que permita saber si un año es bisiesto.(Para que un año sea bisiesto debe ser divisible por 4 y no debe ser divisible por 100, excepto que también sea divisible por 400.)

Algoritmo Año_Bisiesto
	
	Escribir 'Ingresa el año: '
	
	Leer año
	
	A1<-año%4
	
	A2<-año%100
	
	A3<-año%400
	
	Si [(A1=0)&(A2=0)&(A3=0)]|[(A1=0)&(A2<>0)] Entonces
		
		Escribir año,' es año bisiesto'
		
	SiNo
		Escribir año,' no es año bisiesto'
		
	Fin Si
	
FinAlgoritmo


Escribe un programa que permita al usuario ingresar 6 números enteros, que pueden ser positivos o negativos. Al finalizar, mostrar la sumatoria de los números negativos y el promedio de los positivos.
Algoritmo SumayPromedio
	cont <- 1
	
	cont_pos <- 0
	
	sum_pos <- 0
	s um_neg <- 0 
	Mientras cont<=6 Hacer
		Segun cont  Hacer
			1:
				lugar <- ' primer'
			2:
				lugar <- 'segundo'
			3:
				lugar <- 'tercer'
			4:
				lugar <- 'cuarto'
			5:
				lugar <- 'quinto'
			6:
				lugar <- 'sexto'
		FinSegun
		Escribir 'Dame el ',lugar,' número: '
		Leer num
		Si num>=0 Entonces
			sum_pos <- sum_pos+num
			cont_pos <- cont_pos+1
		SiNo
			sum_neg <- sum_neg+num
		FinSi
		cont <- cont+1
	FinMientras
	prom <- sum_pos/cont_pos
	Escribir 'El promedio de los números positivos es: ',prom
	Escribir 'La sumatoria de los números negativos es: ',sum_neg
FinAlgoritmo



Escribe un programa que permita al usuario ingresar los montos de las compras de un cliente (se desconoce la cantidad de datos que cargará, la cual puede cambiar en cada ejecución), cortando el ingreso de datos cuando el usuario ingrese el monto 0. Si ingresa un monto negativo, no se debe procesar y se debe pedir que ingrese un nuevo monto.

Algoritmo Monto_total
	
	total<-0
	
	Repetir
		
		Escribir "ingresa monto: "
		
		Leer monto
		
		Si monto<0 Entonces
			
			Escribir 'Ingresa otro monto: '
			
			Leer monto
			
		SiNo
			
		Fin Si
		
		total<-total+monto
		
	Hasta Que monto=0
	
	Escribir 'El monto total es: ',total
	
FinAlgoritmo

Hallar Aumento al Sueldo de un empleado; si el sueldo es mayor a $500.000 su aumento será del 12%, pero si su sueldo es menor El aumento será del 15%. 

Algoritmo Aumneto_de_sueldo
	
	Escribir 'Introduzaca su sueldo actual: '
	
	Leer sueldo
	
	Si sueldo >=500 Entonces
		
		nuevo<-sueldo + 0.12*sueldo
		
		Escribir 'Su nuevo sueldo será de $', nuevo
		
	SiNo
		
		nuevo<-sueldo + 0.15*sueldo
		
		Escribir 'Su nuevo sueldo será de $', nuevo
		
	Fin Si
	
FinAlgoritmo

	
