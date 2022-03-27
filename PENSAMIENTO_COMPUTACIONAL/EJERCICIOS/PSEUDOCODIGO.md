
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.
* 1 Inicio
* 2 Declarar (numero,resultado)
* 3 Mostrar "Ingrese un número"
* 4 Asignar (num)
* 5 resultado = numero * 9
* 7 Mostrar "El resultado de multiplicar",num," por 9 ",resultado
* 6 Fin

Algoritmo ejercicio1

	Escribir "Ingresa número"
  
	Leer num
  
	resultado<-num * 9 
  
	Escribir "el resultado de multiplicar " ,num, " por 9 es ",resultado
  
FinAlgoritmo


![image](https://user-images.githubusercontent.com/90996552/160259938-b3ead15a-149f-4673-9d1a-59318a4549cc.png)


3. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 


Algoritmo ejercicio2

	Escribir "Ingresa un número"
  
	Leer num1
  
	contador<-0
  
	Mientras contador<10 Hacer
  
		resultado<- resultado+num1
    
		Escribir "Ingrese un numero"
    
		Leer num1
    
		contador<-contador+1
    
		
	Fin Mientras
	
	Escribir "El resultado de la suma de 10 números es ",resultado

	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/90996552/160260687-f7297143-3f8b-4a1f-9280-a5cd246a109a.png)


5. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.
* 1 Inicio
* 2 Declarar (cal1,cal2,cal3,cal4, promedio)
* 3 Mostrar "Ingresa tu calificación"
* 4 Asignar (cal1,cal2,cal3,cal4)
* 5 promedio = (cal1+cal2+cal3+cal4)/4, si promedio>=6 mostrar "Felicidades", sino mostrar "reprobado"
* 6 Fin  

Algoritmo ejercicio3
	
	Escribir "Ingresa tu calificación del primer periordo"
  
	Leer cal1
  
	Escribir "Ingresa tu calificación del segundo periodo"
  
	Leer cal2
  
	Escribir "Ingresa tu calificación del tercer perioro"
  
	Leer cal3
  
	Escribir "Ingresa tu calificación del cuarto periodo"
  
	Leer cal4
  
	promedio<-(cal1+cal2+cal3+cal4)/4
	
	Si promedio >= 6 Entonces
  
		Escribir "Felicidades tu promedio es ",promedio
    
	SiNo
  
		Escribir "Tu promedio es ",promedio, " estas reprobado"
    
	Fin Si
  
  FinAlgoritmo
  
 ![image](https://user-images.githubusercontent.com/90996552/160261204-8d6e89e3-4fd5-43c1-ab0d-67673a15c4c8.png)
 
	
	
7. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.
* 1 Inicio
* 2 Declarar(num)
* 3 Mostrar "Ingresa número"
* 4 Asignar (num)
* 5 Si num/2 y si reciduo es entero mostrar "Número par", sino mostrar "número impar"
* 6 Fin
9. Un programa que pida una letra y detecte si es una vocal.

11. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
12. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
13. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
