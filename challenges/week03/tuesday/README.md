<h2>Week challenges (Tuesday) 💻</h2>

<h3>Simple calculator with Switch 📝</h3>
<pre>
  <code>
Algoritmo simpleCalculator
	number1 = 0
	number2 = 0
	Imprimir 'Write first number'
	Leer number1
	Imprimir 'Write second number'
	Leer number2
	Imprimir  'Selected operation'
	Imprimir '1.Sum (+) 2.Subtract (-) 3.Multiplication (*) 4.Division (/)'
	Leer operation
	Si operation >= 1 & operation <= 4  Entonces
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
FinAlgoritmo  
   </code>
</pre>

</br>

<h3>Multi Option Program 📝</h3>
<pre>
  <code>
Algoritmo multiOptionProgram
	Imprimir '---Multi Option Program---'
	Imprimir 'Selected option'
	Imprimir '1. Sum two numbers'
	Imprimir '2. Print the day of the week given the day number'
	Imprimir '3. Print the length of a given text'
	Leer  option
	Si option >= 1 & option <= 3  Entonces
		Segun option Hacer
			1: 
				Imprimir 'Write first number'
				Leer number1
				Imprimir 'Write second number'
				Leer number2
				Imprimir 'Result sum' number1 + number2
			2: 
				Imprimir 'Write number day'
				Leer day
				Segun day Hacer
					1:
						Imprimir 'Monday'
					2:
						Imprimir 'Tuesday'
					3:
						Imprimir 'Wednesday'
					4:
						Imprimir 'Thursday'
					5:
						Imprimir 'Friday'
					6:
						Imprimir 'Saturday'
					7:
						Imprimir 'Sunday'
				FinSegun
			3: 
				Imprimir 'Write the text'
				Leer text
				Imprimir 'Length is ' Longitud(text)
			De Otro Modo:
				Imprimir 'operation not exist'
		FinSegun
	SiNo
		Imprimir 'option not exist'
	FinSi
FinAlgoritmo
   </code>
</pre>