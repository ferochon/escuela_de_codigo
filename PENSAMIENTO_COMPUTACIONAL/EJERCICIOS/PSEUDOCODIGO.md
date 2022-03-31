
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

Algoritmo Multiplicado_por_9
	
  Escribir 'Introduce un número'
	
  Leer num
	
  multi_9= num*9
	
  Escribir num ' x 9 = ',multi_9

FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203503/161151599-9ee890fd-2217-4258-b7c7-ab60fd765f08.png)


2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 

Algoritmo Suma_Diez_Cantidades
	
	cont1<-1
	
	suma<-0
	
	Mientras cont1<= 10 Hacer
		
		Segun cont1 Hacer
			
			1:
				posicion <- 'primera'
			2:
				posicion <- 'segunda'
			3:
				posicion <- 'tercera'
			4:
				posicion <- 'cuarta'
			5: 
			        posicion <- 'quinta'
			6:	
				posicion <- 'sexta'
			7:	
				posicion <- 'séptima'
			8:  	
				posicion <- 'octava'
			9:	
				posición <- 'novena'
			10:	
				posicion <- 'décima'
				
			De Otro Modo:

		Fin Segun
		
		Escribir 'Dame la ',posicion,' cantidad: '
		
		Leer cantidad
		
		suma= suma + cantidad
		
		cont1= cont1+1
	
	Fin Mientras
	
	Escribir 'La suma total de los diez números es: ', suma

FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203503/161159461-94f1e31a-4adc-4201-bc74-4a8de056245f.png)


3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

1. Inicio
2. Declarar(calif1,calif2,calif3,calif4,promedio)
3. Asignar (calif1,calif2,calif3,calif4)
4. promedio=(calif1+calif2+calif3+calif4)/4
5. SI (proemdio>=6) ENTONCES Mostrar ('El promedio es: ', promedio,' felicidades! Has aprobado el curso')
   SINO('El promedio es: ', promedio,' lo siento, reprobaste el curso')
   FIN SI
6. Fin

![image](https://user-images.githubusercontent.com/101203503/161163435-9a80dafd-5d6b-42c3-aeba-e3b0672c7f96.png)

4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.
5. Un programa que pida una letra y detecte si es una vocal.
6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
