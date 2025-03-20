# Desarollo
  Class I:
     (Ejercicios Practicos)
      1. Ejercicio de Descomposición: Descomponer el proceso de cocinar una receta simple (ejemplo: hacer una tortilla) en pasos detallados.
      ![img044](https://github.com/user-attachments/assets/36ade646-6b1e-4f9a-a02b-c90ca37b4df7)
      2.Ejercicio de Abstracción: Explicar cómo funciona un semáforo sin mencionar detalles internos del circuito electrónico.
      ![img043](https://github.com/user-attachments/assets/2f55e754-7de7-46d8-a718-5727f9d1ac9d)
      3.Ejercicio de Modelado: Dibujar un diagrama de flujo que represente el proceso de inscripción a una universidad.
      ![WhatsApp Image 2025-03-19 at 9 20 54 PM](https://github.com/user-attachments/assets/11943cf6-803e-4770-9739-bb80341acf41)
      4. Ejercicio de Patrones: Identificar patrones en una lista de números y describir la relación entre ellos.
      ![img047](https://github.com/user-attachments/assets/8e9f0e7b-b6e9-479b-ada7-c61371cf07fb)
  Class II:
    (Ejercicios Practicos)
    1.Escribir en pseudocódigo un algoritmo que determine si un número es par o impar.
    [Uploading Numero_Par_Impar Class II #1.psc…]()
    
    Algoritmo Numero_Par_Impar
    
    Escribir "�que numero deseas comprobar?"
  
	Leer N
 
	si N>2 Entonces
 
		N=N/2
  
		Repetir
  
		N=N/2
  
	Hasta Que N<=2
 
	FinSi
 
	si N=2 Entonces Escribir "par"
 
	sino escribir "impar"
 
	FinSi

FinAlgoritmo
2.Dibujar un diagrama de flujo que represente el proceso de inscripción en una plataforma en línea.
![WhatsApp Image 2025-03-20 at 12 09 51 PM](https://github.com/user-attachments/assets/f6b3bc36-61a6-4e5f-9039-90b2edcc5c66)

3.Analizar la eficiencia de los siguientes algoritmos y expresarla en notación Big-O:
Búsqueda secuencial en una lista.
Ordenamiento por burbuja.
Búsqueda binaria en un array ordenado.
![img048](https://github.com/user-attachments/assets/b4a9fd05-4bf8-4786-b3df-8caa48acd957)

4.Implementar en pseudocódigo un algoritmo que calcule el factorial de un número.
[Uploading Factorial Class II #4.psc…]()

    Algoritmo Factorial

    Escribir "N�mero a factorizar: "
  
	Leer numero
 
	f=1
 
	i<numero-1
 
	f*=i
 
	i+1=i
 
	Entonces
 
	Escribir "El Factorial de {numero}, es {f}"
 
	
FinAlgoritmo

Class III
(Ejercicios Practicos)
1-2.Declara una variable para almacenar la edad de una persona y asigna un valor.
Escribe una expresión que combine operadores aritméticos y relacionales.
[Uploading edad_persona Class III #1-2.psc…]()

    Algoritmo edad_persona

	  Definir edad Como Entero
 
	edad <- 19
 
	si edad>18
 
		escribir eres_mayor_de_edad
  
	SiNo
 
		Escribir eres_menor_de_edad
  
	FinSi
	
FinAlgoritmo

3.Convierte el número decimal 13 a binario.

[Uploading trece_a_binario Class III #3.psc…]()

    Algoritmo trece_a_binario

	numero = 13
 
	binario = numero / 2
 
	si binario < 1
 
		Escribir binario de 13
  
		Escribir "ejemplo practico"
  
		Escribir "si en nuestra division sobra 1 numero decimal escribiremos un 1, sino escrbimos 0, y escribimos de abajo hacia arriba"
  
		binario = 13/2
  
		binario = 6/2
  
		binario = 3/2
  
		binario = 1/2
  
		binario = 1101
  
		Escribir binario
  
	FinSi
	
FinAlgoritmo

4.Implementa un algoritmo en PSeInt que utilice operadores aritméticos y lógicos para calcular si un número es par o impar.
[Uploading Numero_Par_O_Impar.py…]()

    numero = int(input("numero: "))

    if numero >= 10:

    if numero <=20:
    
    print("Esta en el rango")
     
    if numero > 20:

     print("No esta en el rango")






