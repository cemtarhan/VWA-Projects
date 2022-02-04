# VWA-Projects
Cem Tarhan 12B 3447 / St. Georg's Kolleg Istanbul / VWA Projekte

Das Projekt umfasst 2 Teile: 

1) Erkennung der Horizontlinie

Bei der Horizonterkennung kommen Open-CV-Bildbearbeitungsfunktionen wie Dilatation und Erosion zum Einsatz, damit die "Canny"-Kantenerkennungsfunktion und der Hough-Transform-Algorithmus genauere Ergebnisse liefern. Das Zielbild wird außerdem durch einen Medianfilter gefiltert, der das Bild insgesamt glättet. Die letzte Funktion sucht nach der längsten Linie im Bild und markiert sie als Horizontlinie.  

2) Bildsegmentierung

Der Bildsegmentierungsteil des Projekts nutzt verschiedene Bildoperationen unter Verwendung von Open-CV-Bibliotheken, darunter Otsus Thresholding-Methode, Dilatation und auch Erosion. Nach den verschiedenen Bildoperationen sucht der Code nach sogenannten "Pixelgruppen", die in dem im Projekt verwendeten Beispiel die Lastwagen sind, und jede Gruppe wird mit einer anderen Farbe markiert, die im endgültigen Ausgabebild zu sehen ist. 


********************************************************************************************************************************************************************

Die obigen Dateien sind für die Verwendung in Google Colaboratory gedacht und werden in Google Drive gespeichert, um die Laufzeit des Projekts zu beschleunigen. Um ein Bild aus Google Drive zu ziehen, wurde eine Bibliothek verwendet, um die Open-CV-Bildlesefunktion mit den in der Cloud gespeicherten Dateien zu verbinden. Um den Code lokal auf einem Computer auszuführen, muss die Funktion cv2.imread mit dem Pfad zum Zielbild versehen werden. 


