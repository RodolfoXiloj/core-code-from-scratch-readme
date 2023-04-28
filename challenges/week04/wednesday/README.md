<h2>Week challenges (Wednesday) 💻</h2>

<h3>Distance to zero 📝</h3>
<pre>
  <code>
Algoritmo distanceZero
	Dimension numbers[5]
	Imprimir '---Distance to zero---'
	Imprimir 'Write number 1'
	Leer numbers[1]
	Imprimir 'Write number 2'
	Leer numbers[2]
	Imprimir 'Write number 3'
	Leer numbers[3]
	Imprimir 'Write number 4'
	Leer numbers[4]
	Imprimir 'Write number 5'
	Leer numbers[5]
	max = 0
	Para i <- 1 Hasta 5 Con Paso 1 Hacer
		Si ABS(numbers[i]) > ABS(max) Entonces
			max <- numbers[i]
			Imprimir entro
		FinSi
	Fin Para
	Imprimir 'Result ' max
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Toss Coin 📝</h3>
<pre>
  <code>
Algoritmo tossCoin
	Imprimir '---Toss Coin---'
	Imprimir 'Write the first player'
	Leer first_name
	Imprimir 'Write the first amount'
	Leer first_number
	Imprimir 'Write the second player'
	Leer second_name
	Imprimir 'Write the second amount'
	Leer second_number
	
	Si first_number <= 0 & second_number <= 0 Entonces
		Imprimir 'Game canceled'
	SiNo
		Si first_number <= 0 Entonces
			Imprimir 'Lost first player ' first_name
		SiNo
			Si second_number <= 0 Entonces
				Imprimir 'Lost second player ' second_name
			SiNo
				Si Aleatorio(1,2) == 1
					Imprimir 'Winner first player ' Mayusculas(first_name) ' amount ' first_number
				SiNo
					Imprimir 'Winner second player ' Mayusculas(second_name) 'amount ' second_number
				FinSi
			FinSi
		FinSi
	FinSi
FinAlgoritmo
   </code>
</pre>
