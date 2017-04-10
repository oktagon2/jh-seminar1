## Seminar 1

Verwende dieses Template als Ausgangsbasis für unser Code Camp in Cloud9

1) Öffne index.html file

2) Klicke auf "Preview"

3) Gebe eine Zahl ein zwischen 1-10 und betätige den Knopf

Weitere Aufgaben:

4) Schaue auf https://jsonplaceholder.typicode.com/users nach welche weiteren 
Attributte vorhanden sind.

5) Zeige neben dem Namen auch die Username und E-Mail und den Firmenname an.

## Hinweise

Mit der Punktnotation kann man an Element in einem Javascript Objekt navigieren.

Mit der Backtick Notation geht es einfacher, die aber erst seit ES6 vorhanden 
ist. Beispiel: 

			document.getElementById("userName").innerHTML = `
				<p>Name: ${data.name}</p>
				<p>Email: ${data.email}</p>
				<p>Firma: ${data.company.name}</p>
				`;

