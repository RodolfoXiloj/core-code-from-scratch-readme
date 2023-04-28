<h2>Week challenges (Tuesday) 💻</h2>

<h3>Total Price 📝</h3>
<pre>
  <code>
Funcion total <- TotalPrice (price, vat)
	SI price > 3000 Entonces
		subtotal = price + (vat * price / 100)
		total = subtotal - (0.10 * subtotal)
	SiNo
		total = price + (vat * price / 100)  
	FinSi
Fin Funcion
Algoritmo example_TotalPrice
	Imprimir TotalPrice(5000,21)
FinAlgoritmo
   </code>
</pre>

</br>

<h3>Reverse direction and size 📝</h3>
<pre>
  <code>
Funcion reverse <- ReverseDirectionAndSize (char)
	Para i <- Longitud(char)  Hasta 0 Con Paso - 1 Hacer
		l = Subcadena(char, i, i)
		Si l = Mayusculas(l) Entonces
			reverse = reverse + Minusculas(l)
		SiNo
			reverse = reverse + Mayusculas(l)
		FinSi
	Fin Para
Fin Funcion

Algoritmo ReverseDirection
	Imprimir ReverseDirectionAndSize('HelLO')
FinAlgoritmo
   </code>
</pre>