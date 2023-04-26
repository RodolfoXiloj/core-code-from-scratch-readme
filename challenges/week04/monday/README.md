<h2>Week challenges (Monday) 💻</h2>

<h3>Average sales and commission 📝</h3>
<pre>
    <code>
Algoritmo averageSalesCommission
	Imprimir '---Average sales and commission---'
	Imprimir 'Write the total number of sales'
	Leer sales
	total_sales = 0
	Para i<-1 Hasta sales Con Paso 1 Hacer
		Imprimir 'Write the total from sales ' i
		Leer sale
		total_sales = total_sales + sale
	Fin Para
	Imprimir total_sales / sales
	Si sales > 5 Entonces
		Imprimir 'The averages sale is: ' 0.15 * total_sales 
	SiNo
		Imprimir 'The comision for seller is: ' 0.10 * total_sales 
	FinSi
FinAlgoritmo
    </code>
</pre>


<h3>Even or odd 📝</h3>
<pre>
  <code>
Algoritmo evenOdd
	Imprimir '---Even or odd---'
	number = 0
	Repetir
		Imprimir 'Write a number between 1 and 50'
		Leer number
		Si number < 1 | number > 50
			Imprimir '--ERROR--'
			Imprimir 'Number is not between 1 and 50'
			Imprimir '----'
		FinSi
	Hasta Que number >= 1 & number <= 50
	
	Para step = 1 Hasta number Con Paso 1 Hacer
		Si number %  2 == 0 & step %  2 == 0 Entonces
			Imprimir step
		FinSi
		
		Si number %  2 == 1 & step %  2 == 1 Entonces
			Imprimir step
		FinSi
	FinPara

FinAlgoritmo
   </code>
</pre>
