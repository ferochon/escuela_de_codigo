Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo

Inicio

declarar(NumIncog, NumPrueba, intentos) Int

Mostrar("Dame un número: ")

Asignar(NumPrueba)

Asignar(azar(NumIncog))

Intentos=0

Mientras(NumIncog!=NumPrueba&&intentos<=10){SI NumPrueba>NumIncog ENTONCES Mostrar("El número que ingresaste es mayor. Intenta de nuevo")

                                                                  SINO Mostrar("El número que ingresaste es menor. Intenta de nuevo") FIN SI

intentos= intentos +1

Mostrar("llevas: ",intentos," intentos")

Mstrar("Dame un número: ")
		
Asignar(NumPrueba)

}
Si (NumPrueba && NumIncog) ENTONCES Mostrar("Felicidades!Le atinaste en ", intentos," intentos, el número es ",NumIncog)

SI NO Mostrar("Lo siento, excediste  el número de intentos, el numero era :",NumIncog) FIN SI

FIN


Pseudocódigo

Algoritmo Juego3
	
	Escribir'Dame un número: '
	
	Leer NumPrueba
	
	NumIncog= azar(100)+1
	
	intentos=0
	
	Mientras (NumPrueba<>NumIncog & intentos <=10) Hacer
		
		Si NumPrueba>NumIncog Entonces
			
			Escribir 'El número que ingresaste es mayor.Intenta de nuevo'
			
		SiNo
			
		Escribir 'El número que ingresaste es menor.Intenta de nuevo'
		
	    Fin Si
		
		Intentos<-intentos+1
		
		Escribir'llevas: ',intentos," intentos"
		
		Escribir'Dame un número: '
		
		Leer NumPrueba
		

	Fin Mientras
	
	Si NumPrueba == NumIncog Entonces
		
		Escribir 'Felicidades!Le atinaste el número es", NumIncog, en ',intentos," intentos"
		
	SiNo
		
		Escribir 'Lo siento, excediste  el número de intentos, el numero era :',NumIncog
		
	Fin Si
	
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/101203503/160972101-40835e54-ac9e-4c45-88f4-829d7d15c4b5.png)


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing


