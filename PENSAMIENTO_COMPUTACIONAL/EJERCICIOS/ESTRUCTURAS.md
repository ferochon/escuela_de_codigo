# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo

1.Inicio

2.Declarar(numero)float

3.Mostrar("Dame un número")

4.Asignar(numero)

5.Si(numero>0),
  
  Entonces(numero,"Es psitivo") 
 
  SINO (Si(numer<0)
        
        Entonces Mostrar("es negativo")
        
        SINO Mostrar("es cero")


        FINSI 
    
    FINSI 
  
  FINSI
 
 6.Fin
  
![image](https://user-images.githubusercontent.com/101203503/161176022-bb764430-b3a5-4424-bd97-52e7816c2022.png)





* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

1. Inicio

2. Declarar(letra)char  

3. Mostrar("Ingresa una letra")

4. Asignar(letra)

5. Si (letra == "s" || letra == "n") Entonces (Mostrar("Letra correcta") SINO ("Letra incorrrecta")

6. Fin  

[Uploading Untitled Diagram (1).drawio…]()


![image](https://user-images.githubusercontent.com/101203503/161177985-fe4ca862-f041-401d-99ab-86ae1557c111.png)


* Un programa que pida una letra y detecte si es una vocal. 

1. Inicio

2. Declarar(vocal)Char

3. Mostrar("Ingresa una letra")

4. Asignar(letra)

5. EN CASO DE (letra) HAGA      
 
           "a": Mostrar("Es vocal"); 
       
           "e": Mostrar("Es vocal"); 
       
           "i": Mostrar("Es vocal");
       
           "o": Mostrar("Es vocal";
       
           "u": Mostrar("Es vocal"); 
   
   SINO: Mostrar("No es vocal");
   
   FIN CASO
   
 6.Fin  
    



* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

1. INICIO
 
2. Declarar( n1 n2 n3) int

3. Moostrar("Dame un número: ")

4. Mostrar("Dame otro número: ")

5. Mostrar("Dame otro número: ")

6. Asignar(n1 n2 n3)

7. SI1 (n1<=n2)Y(n2<=n3), ENTONCES1 mostrar( n1 n2 n3) SINO SI2(n1<=n3) ENTONCES2 mostrar (n1 n3 n2) SINO2 mostrar (n3 n1 n2)FINSI2 SINO1
SI3(n3<=n1) ENTONCES3 mostrar (n1 n2 n3) SINO3 SI4(n2<=n3) ENTONCES4 mostrar(n2 n3 n1) SINO4 mostrar(n3 n2 n1) FINSI4 FINSI3 FINSI1

8. FIN

* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
 
1. Inicio

2. Declarar (num) char

3. Mostrar ("Dame un número del 1 al 12")

4. Asignar (num)

5. En CASO DE num HAGA
   
   1: Mostrar ("Enero")
   
   2: Mostrar ("Febrero")
   
   3: Mostrar ("Marzo")
   
   4: Mostrar ("Abril")
   
   5: Mostrar ("Mayo")
   
   6: Mostrar ("Junio")
   
   7: Mostrar ("Julio")
   
   8: Mostrar ("Agosto")
   
   9: Mostrar ("Septiembre")
   
   10: Mostrar ("Octubre")
   
   11: Mostrar ("Noviembre")
   
   12: Mostrar ("Diciembre")
   
   SI NO   
   
   FIN CASO

6. Fin  


* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

1. Inicio

2. Declarar(votO)Char

3. Mostrar("¿Por quien vota A,B o C?: ") 

4. Asignar(voto)

5. EN CASO DE voto HAGA
     
     CASO 'A':  Mostrar("Usted ha votado por el partido ROJO")
     
     CASO 'B':  Mostrar("Usted ha votado por el partido VERDE")
     
     CASO 'C':  Mostrar("Usted ha votado por el partido AZUL")
     
     SI NO  Mostrar("Opción ERRONEA")
     
   FIN CASO  

6. Fin
 


* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.

 1. Inicio
 
 2. Declarar(correo, contraseña, contraeña_de_usuario, correo_de_usuario) string

 3. correo_de_usuario = correo_de_usuario@xmail.com
 
 4. contraeña_de_usuario = Que tal mundo
 
 5. Mostrar('Introduce tu e-mail: ')
  
 6. Asignar(correo)
 
 7. Mostrar('Introduce tu contraseña: ')

 8. Asignar(contraseña)

 9. SI (correo == correo_de_usuario && contraseña == contraeña_de_usuario)ENTONCES Mostrar ("e-mail y password correctos")

    SI NO Mostrar ("e-mail o password incorrectos")
    
    FIN SI
 
 10. Fin
 




