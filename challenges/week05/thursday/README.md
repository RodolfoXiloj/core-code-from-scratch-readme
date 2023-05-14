<h2>Week challenges (Thursday) 💻</h2>

<h3>Multiplication Tables with For 📝</h3>
<pre>
  <code>
Algoritmo multiplicationTables
	Imprimir '---Multiplication Tables---'
	Imprimir 'Whrite the number'
	Leer number
	Para i = 1 Hasta 10 Con Paso 1 Hacer
		Imprimir i ' * ' number ' = ' number * i
	FinPara
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Ascending and Descending Numbers 📝</h3>
<pre>
  <code>
Algoritmo ascendingDescending
	Imprimir '---Ascending and Descending Numbers---'
	Imprimir 'Whrite the number'
	Leer number
	Imprimir 'Selected Operation'
	Imprimir '1. Numbers in ascending'
	Imprimir '2. Numnbers in descending'
	Leer operation
	Si operation = 1 Entonces
		Para i = 0 Hasta number Con Paso 1 Hacer
			Imprimir i
		FinPara
	SiNo
		Para i = number Hasta 0 Con Paso -1 Hacer
			Imprimir i
		FinPara
	FinSi
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Greetings 📝</h3>
<pre>
  <code>
Algoritmo greetings
	count = 0
	Repetir
		Imprimir '---Greetings---'
		Imprimir 'Whrite the current time'
		Leer time
		Si time <= 12 Entonces
				Imprimir 'Buenos dias!'
		SiNo
			Si time <= 18 Entonces
				Imprimir 'Buenas tardes!'
			SiNo
				Si time <= 23 Entonces
					Imprimir 'Buenas noches!'
				SiNo
					Imprimir 'Time not exist'
				FinSi
			FinSi
		FinSi
		count = count + 1
		Imprimir 'Do you want write another time?'
		Imprimir '1. Yes 2. No'
		Leer question
	Hasta Que question == 2
	Imprimir 'the number of times the program has greeted ' count
FinAlgoritmo
   </code>
</pre>