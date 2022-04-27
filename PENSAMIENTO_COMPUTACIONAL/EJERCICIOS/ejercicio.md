Algoritmo sin_titulo
	cal <- 0
	i <- 0
	mayor7 <- 0
	menor7 <- 0
	Mientras i<10 Hacer
		i <- i+1
		Escribir 'Ingresa calificacion ',i
		Leer cal
		Si cal<7 Entonces
			menor7 <- menor7+1
		SiNo
			mayor7 <- mayor7+1
		FinSi
	FinMientras
	Escribir 'El total cal de mayor a 7',mayor7
	Escribir 'El total cal de menor a 7',menor7
FinAlgoritmo
