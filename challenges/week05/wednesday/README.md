<h2>Week challenges (Wednesday) 💻</h2>

<h3>Sum of pairs 📝</h3>
<pre>
  <code>
Funcion sum <- sumOfPairs()
	Imprimir '---Sum of pairs---'
	sum = 0
	Repetir
		Imprimir  'Wtite a number between 1 and 100'
		Leer number
		Si number <= 0 | number > 100 Entonces
			Imprimir 'Invalid number'
		SiNo
			SI number % 2 = 0
				sum = sum + number;
			FinSi
		FinSi
	Hasta Que number <= 0 | number > 100
Fin Funcion
Algoritmo exampleSumOfPairs
	Imprimir sumOfPairs()
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Mid point 📝</h3>
<pre>
  <code>
Funcion point <- midPoint(start, end)
	Imprimir '---Mid point---'
	SI start < 0 | end < 0 Entonces
		point = 0
	SiNo
		point = (start + end) / 2
	FinSi
Fin Funcion
Algoritmo exampleMidpPoint
	Imprimir midPoint(40,80)
FinAlgoritmo
   </code>
</pre>