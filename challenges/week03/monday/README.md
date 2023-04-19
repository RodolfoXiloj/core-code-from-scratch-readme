<h2>Week challenges (Monday) 💻</h2>

<h3>Simple calculator 📝</h3>
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
	Si operation == 1 Entonces
		Imprimir number1 + number2
	SiNo
		Si operation == 2 Entonces
			Imprimir number1 - number2
		SiNo
			Si operation == 3 Entonces
				Imprimir number1 * number2
			SiNo
				Si operation == 1 Entonces
					Imprimir number1 / number2
				SiNo
					Imprimir 'operation not exist'
				FinSi
			FinSi
		FinSi
	FinSi
FinAlgoritmo    
    </code>
</pre>


<h3>Special number 📝</h3>
<pre>
  <code>
Algoritmo specialNumber
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'
	SiNo
		Si (n < 1000) & (n % 10 == 0) Entonces
			Imprimir 'This number is almost special'
		SiNo
			Imprimir 'Just a regular number'
		FinSi
	FinSi
FinAlgoritmo
   </code>
</pre>
