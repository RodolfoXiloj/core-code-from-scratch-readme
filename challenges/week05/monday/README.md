<h2>Week challenges (Monday) 💻</h2>

<h3>Time Converter 📝</h3>
<pre>
    <code>
Funcion time <- timeConverter ( number )
	time = ''
	days = 0
	hours = 0
	seconds = 0
	minutes = 0
	Si number >= 86400 Entonces
		days = Trunc(number / 86400)
		number = ABS((days * 86400) - number)
	FinSi
	Imprimir number
	Si number >= 3600 Entonces
		hours = Trunc(number / 3600)
		number = ABS((hours * 3600) - number)
	FinSi
	Si number >= 60 Entonces
		minutes = Trunc(number / 60)
		number = ABS((minutes * 60) - number)
	FinSi
	seconds = number
	
	time = Concatenar('Days: ',ConvertirATexto(days))
	time = Concatenar(time,Concatenar(', Hours: ',ConvertirATexto(hours)))
	time = Concatenar(time,Concatenar(', Minutes: ',ConvertirATexto(minutes)))
	time = Concatenar(time,Concatenar(', Seconds: ',ConvertirATexto(seconds)))
Fin Funcion
Algoritmo exampleTimeConverter
	Imprimir timeConverter(150000)
FinAlgoritmo
    </code>
</pre>


<h3>Compare distances 📝</h3>
<pre>
  <code>
Funcion bool <- compareDistances ()
	Imprimir '---Compare distances---'
	positive = 0
	negative = 0
	Para i<-1 Hasta 5 Con Paso 1 Hacer
		Imprimir 'Write a number for the position ' i
		Leer number
		Si number >= 0 Entonces
			positive = positive + number
		SiNo
			negative = negative + number
		FinSi
	Fin Para
	Si positive > ABS(negative) Entonces
		bool = 'True'
	SiNo
		bool = 'False'
	FinSi
Fin Funcion
Algoritmo exampleCompareDistances
	Imprimir CompareDistances()
FinAlgoritmo
   </code>
</pre>
