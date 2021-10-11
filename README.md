Algoritmo media_3_numeros
	Escribir "digite 3 numeros para calcular la media"
	leer a, b, c
	sum<-a+b+c
	med<-sum/3
	Escribir "la media de los numeros es: " med
FinAlgoritmo
Algoritmo minutos_horas
	Escribir "digite la cantidad de minutos q desea convertir"
	leer a
	b<-a
	Mientras a>=60 Hacer
		h<-h+1
		a<-a-60
	Fin Mientras
	escribir b "minutos son " h " horas y " a " minutos"
FinAlgoritmo

Algoritmo per_area
	escribir "ingrese la distancia de la altura del triangulo"
	definir a, b Como Real
	leer a
	escribir "ingrese la distancia de la base del triangulo"
	leer b
	definir per, area Como Real
	per<-(2*b)+(2*a)
	area<-b*a
	Escribir  "el area del triangulo es " area " el perimetro del triangulo es " per
		
FinAlgoritmo
Algoritmo saludar
	Escribir "digita tu nombre!"
	definir a Como Caracter
	leer a
	Escribir  "hola " a " como va todo?"
	
FinAlgoritmo
Algoritmo sum_res_div
	escribir "ingrese dos numeros para realizar los procesos matematicos"
	leer a,b
	sum<-a+b
	res<-a-b
	mul<-a*b
	div<-a/b
	escribir "la suma es:  " sum
	escribir "la resta es: " res
	escribir "la multiplicacion es:" mul
	Escribir "la division es " div
	
FinAlgoritmo
Algoritmo total_compra
	escribir "digite el total de la compra para aplicar el descuento"
	leer a
	des<-a*.15
	Escribir "el total a pagar con el descuento es de: " a-des
	
FinAlgoritmo
Algoritmo vendedor_comision
	escribir "digite las 3 ventas realizadas"
	leer a, b, c
	escribir "digite cual es el saldo base"
	leer d
	com=(a+b+c)*.10
	Escribir "la comision de las ventas es: " com
	escribir "el sueldo que recibiria es: " d+com
	
FinAlgoritmo
