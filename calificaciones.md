Algoritmo Promedio_ponderado
	Definir a, b, c, d, e, f, g, h Como Real
	Escribir "Ingrese la nota obtenida en el parcial I y su valor (%):"
	Leer a, b
	Escribir "Ingrese la nota obtenida en el parcial II y su valor (%):"
	Leer c,d
	Escribir "Ingrese la nota obtenida en participación y su valor (%):"
	Leer e,f
	Escribir "Ingrese la nota obtenida en el exámen final y su valor (%):"
	Leer g,h
	ParcialI <- (a * b)/100
	ParcialII <- (c * d)/100
	Participacion <- (e * f)/100
	Exfin <- (g * h)/100
	Promedio <- ParcialI + ParcialII + Participacion + Exfin
	Escribir "Su promedio es " Promedio
FinAlgoritmo
