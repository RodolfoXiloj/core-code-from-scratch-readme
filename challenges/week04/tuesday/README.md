<h2>Week challenges (Tuesday) 💻</h2>

<h3>Full name 📝</h3>
<pre>
  <code>
Algoritmo fullName
	Imprimir '---Full name---'
	Imprimir 'Write your first name'
	Leer first_name
	Imprimir 'Write your last name'
	Leer last_name
	new_fname = Mayusculas(Subcadena(first_name,0,1)) + Minusculas(Subcadena(first_name,2,Longitud(first_name)))
	new_lname = Mayusculas(Subcadena(last_name,0,1)) + Minusculas(Subcadena(last_name,2,Longitud(last_name)))
	Imprimir new_fname ' ' new_lname
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Throw dice 📝</h3>
<pre>
  <code>
Algoritmo throwDice
	Imprimir '---Throw dice---'
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		dice1 = Aleatorio(1,6)
		dice2 = Aleatorio(1,6)
		Si dice1 == dice2 Entonces
			Imprimir dice1 ' ' dice2 ' the dice are the same'
		SiNo
			Imprimir dice1 ' ' dice2
		FinSi
	Fin Para
FinAlgoritmo
   </code>
</pre>