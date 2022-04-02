
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

Algoritmo promedio4
	Escribir "ingresa la calificación del primero periodo"
	
	Leer cal1
	
	Escribir "ingresa la calificación del segundo periodo"
	
	Leer cal2
	
	
	Escribir "ingresa la calificación del tercer periodo"
	
	Leer cal3
	
	Escribir "ingresa la calificación del cuarto periodo"
	
	Leer cal4
	
	promedio<-(cal1 + cal2 + cal3 + cal4)/4
	
	Si promedio >=6 Entonces
		
		Escribir "Tu promedio es: ",promedio
		
		Escribir "Feliciades has aprobado" 
	
	SiNo
		
		Escribir "Tu promedio es: ",promedio
		
		Escribir "has reprobado, lo siento" 
	
	Fin Si

FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203503/161388720-6b81342f-0290-489a-9212-3b00c54f413e.png)


4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo sin_titulo
	
	Escribir "Dame el número: "
	
	Leer num
	
	resultado<-num%2
	
	Si resultado=0 Entonces
		
		Escribir "Es un número par" 
	
	SiNo
		
		Escribir "Es un número impar"
	
	Fin Si

FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203503/161391982-51e56da4-f1e5-4c12-81b9-a24c37868714.png)


6. Un programa que pida una letra y detecte si es una vocal.

Algoritmo Es_vocal
	
	Escribir 'Ingresa una letra'
	
	Leer letra
	
	Segun letra Hacer
	
	        'a':
			
			Escribir 'es una vocal'
		
		'e':
			
			Escribir 'es una vocal'
		
		'i':
			
			Escribir 'es una vocal'
		
		'o':
			
			Escribir 'es una vocal'
		
		'u':	
			
			Escribir 'es una vocal'
		
		De Otro Modo:
			
			Escribir 'no es una vocal'
	
	Fin Segun

FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203503/161402918-66bd1311-4927-4eb7-8b8c-73471ad60908.png)


8. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
9. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
10. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
