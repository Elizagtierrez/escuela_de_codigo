Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo JuegoAdivinar


	val= azar(100)+1
	Escribir "Adivina un número del 1 al 100, ingresa un número"
	Leer num
	contador<-9
	Mientras num <> val Y contador>0 Hacer
		Si num < val Entonces
			Escribir "Intentalo de nuevo, ingresa nuevamente un número mayor"
		SiNo
			Escribir "Intentalo de nuevo, ingresa un número menor"
			
			
		Fin Si
		Escribir "Te quedan ",contador, " intentos"
		Escribir "Intentalo de nuevo, ingresa número"
		Leer num
		contador<-contador-1
		
		
	Fin Mientras
	
	
	Si num = val Entonces
		Escribir "Felicidades"
	SiNo
		Escribir "Lo sentimos, perdiste"
	Fin Si

FinAlgoritmo


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
