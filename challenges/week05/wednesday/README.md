<h2>Week challenges (Wednesday) 💻</h2>

<h3>Cashier 📝</h3>
<pre>
  <code>
Funcion balance <- cashier()
	balance = 1000
	Repetir
		Imprimir '---Cashier---'
		Imprimir 'Select an option:'
		Imprimir 'a. To deposit.' 
		Imprimir 'b. Withdraw.'
		Imprimir 'c. Go out.'
		Leer option
		Segun option Hacer
			'a':
				Imprimir 'How much do you want to deposit:'
				Leer  mount
				balance = balance + mount
				
			'b':
				Imprimir 'How much do you want to withdraw'
				Leer  mount
				balance = balance - mount
			'c':
				Imprimir 'Exit'
			De Otro Modo:
				Imprimir 'Invalid option'
		Fin Segun
	Hasta Que option =='c'
Fin Funcion
Algoritmo exampleCashier
	Imprimir cashier()
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Weather average 📝</h3>
<pre>
  <code>
Funcion celcius <- fahrenheitToCelsius (fahrenheit)
	celcius = (fahrenheit - 32) * (5/9)
Fin Funcion
Algoritmo exampleWeatherAverage
	count = 0
	total = 0
	Repetir
		Imprimir '---Weather average---'
		Imprimir 'Select an option:'
		Imprimir 'a. Enter degrees celsius.' 
		Imprimir 'b. Enter degrees fahrenheit.'
		Imprimir 'x. Go out.'
		Leer option
		Segun option Hacer
			'a':
				Imprimir 'Write the value:'
				Leer  value
				count = count + 1
				total = total + value
				
			'b':
				Imprimir 'Write the value:'
				Leer  value
				count = count + 1
				total = total + fahrenheitToCelsius(value)
			'x':
				Imprimir 'Exit'
			De Otro Modo:
				Imprimir 'Invalid option'
		Fin Segun
	Hasta Que option =='x'
	Imprimir total / count
FinAlgoritmo
  </code>
</pre>