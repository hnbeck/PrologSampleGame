
##Simples PROLOG Beispiel für ein Mini-17+4 Kartenspiel##

Beispiele und Illustrationen für den Prolog Heise Dev Online Artikel
 
Author: Hans N. Beck (c)  
Last Change: 04.06.2018  
Lizenz: MIT   

Keine Gewährleistung, zur Benutzung "as is".

##Start##

Starte SWI-Prolog, und gebe "playGame()." in der Kommandozeile ein.
Abwechselnd geben die Spieler ihre Kommandos ein (immer mit Punkt dahinter!)

##Mögliche Weiterentwicklungen

Dies ist nur ein Demonstrator. Es bieten sich einige Verbesserungen an:

In dieser simplen Variante werden Karten nur gelöscht. es muss aber sichergestellt sein, dass das Ziehen einer Karte immer eine Karte liefert, solange noch welche im Deck sind.

Man könnte Karten zugedeckt ziehen und aufdecken wie im richtigen 17+4 usw.

Der Cut Operator benutzt werden, es sind Endlosschleifen möglich etc ;)

Da die Wissensbasis direkt manipuliert wird, muss das Beispiel in einem neu gestarteten SWI-Prolog ausgeführt werden. Man könnte bei Spielstart die Wissensbasis initialisieren oder ganz ohne direkte Manipulation der Wissensbasis arbeiten etc ....