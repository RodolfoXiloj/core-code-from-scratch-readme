<h2>Week challenges (Wednesday) 💻</h2>

<h3>Multiplication Tables 📝</h3>
<pre>
  <code>
Algoritmo multiplicationTables
	Imprimir '---Multiplication Tables---'
	Imprimir 'Whrite the number'
	Leer number
	i = 1
	Mientras i <= 10 Hacer
		Imprimir i ' * ' number ' = ' number * i
		i = i + 1
	FinMientras
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Simple calculator with Do While 📝</h3>
<pre>
  <code>
Algoritmo simpleCalculator
	Repetir
		number1 = 0
		number2 = 0
		Imprimir 'Write first number'
		Leer number1
		Imprimir 'Write second number'
		Leer number2
		Imprimir  'Selected operation'
		Imprimir '1.Sum (+) 2.Subtract (-) 3.Multiplication (*) 4.Division (/)'
		Leer operation
			Segun operation Hacer
				1: 
					Imprimir number1 + number2
				2: 
					Imprimir number1 - number2
				3: 
					Imprimir number1 * number2
				4: 
					Imprimir number1 / number2
				De Otro Modo:
					Imprimir 'operation not exist'
			FinSegun
		SiNo
			Imprimir 'operation not exist'
		FinSi
		Imprimir 'Do you want to perform another operation?'
		Imprimir '1. Yes 2. No'
		Leer question
	Hasta Que question == 2
FinAlgoritmo
   </code>
</pre>
