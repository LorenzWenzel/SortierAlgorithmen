# SortierAlgorithmen
Die gängigsten Sortieralgorithmen implementiert und mit Animationen visualisiert:

## Demonstration: 


https://github.com/LorenzWenzel/SortierAlgorithmen/assets/73563833/8791560c-2482-4227-b174-72ace13bff35



## Selection Sort: 

![image](https://github.com/LorenzWenzel/SortierAlgorithmen/assets/73563833/9e6927bc-cb7c-4f60-864d-0ff1e4c19c66)


## Bubble Sort: 

![image](https://github.com/LorenzWenzel/SortierAlgorithmen/assets/73563833/5c0d5e87-6118-4766-a577-af16c3d6396b)


## Insertion Sort: 

![image](https://github.com/LorenzWenzel/SortierAlgorithmen/assets/73563833/7ab4f1c9-d826-498c-ac2e-b171b54b01bc)



Ich habe mich für die Visualisierung der Sortieralgorithmen anhand einer Animation des Arrays in einer GUI entschieden und gegen z.b. die Visualisierung durch dem Sortieren von Balken, da ich zum einen vollkommen innerhalb der Java.swing Umgebung bleiben wollte, ich aber auch mehr Potential darin sehe die divide & conquer Verfahren zu visualisieren.

Bubble-Sort wird nach jeder Iteration der inneren der beiden Schleifen aktualisiert, also nach jeder Tauschoperation. Beide Elemente der zu tauschenden Felder 
werden dabei grau gefärbt. Finden lediglich Vergleichsoperationen statt, ohne dass es zum Tausch kommt, so wird nur die Übergangszahl grau gefärbt. Wenn nun die kleinste Zahl sich an den Anfang des Arrays getauscht hat, so wird diese grün gefärbt, sodass nach jeder Iteration der äußeren Schleife ein Element sich grün färbt und nach der Länge des Arrays äußerer Iterationen das Array sortiert ist.  

Bei Insertionsort wie Selectionsort sind lediglich die äußeren Schleifen visualisiert, nach jeder Schleife wird der Zustand in der GUI also aktualisiert. So wird nach jeder Einfügeoperation bei Insertionsort das sortierte Teilarray grün gefärbt. Bei SelectionSort findet quasi eine identische Visualisierung statt, nur dass sich die sortierten Felder grau färben bis das Array sortiert ist. 

Die auf divide & conquer basierenden Sortieralgorithmen Merge-Sort und Quicksort sind Stand jetzt noch nicht mit einer Animation hinterlegt, lediglich das Ergebnis und die Zeit in Nanosekunden bis die Methode terminiert lassen sich in der GUI einsehen.

Weitere Ziele für das Projekt sind die Animation der inneren Schleifen von InsertionSort und SelectionSort und eine geeignete Visualisierung der divide & conquer-Algorithmen möglichst ohne Zusatzsoftware und im Rahmen von java.swing.
