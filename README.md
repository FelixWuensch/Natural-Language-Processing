# Natural-Language-Processing
Prüfungsaufgabe 1- fünfter Teil

Um dieses Projekt zu starten, folgen Sie dem Binder Badge:      



# Ausführung der Übungsaufgabe

!!! Alle Befehle werden ausgeführt in dem die Zeile ausgewählt wird und anschließend mit Shift (Großschreibtaste) und Enter gestartet wird !!!

1. Im ersten Schritt müssen alle benötigten Libraries installiert und importiert werden, so dass im Folgenden alle Befehle erfolgreich ausgeführt werden können.

2. Danach werden unsere Daten im CSV Format eingelesen.

3. Daraufhin werden die Daten wieder begutachtet mit den üblichen Funktionen: head(), info() und describe(). Ebenso fügen wir gleich eine weitere Spalte ein die uns die Anzahl der Zeichen der jeweiligen Nachricht abspeichert.

4. Im nächsten Schritt fallen wieder Importe an. Nach erfolgreichem Import der Bibliotheken, nutzen wir diese direkt und erstellen 5 Histogramme, welche uns die Textlängenverteilung anzeigen, nach Sternen sortiert.

5. Im fünften Schritt erstellen wir dann fünf Boxplots um uns die Verteilung der Textlängen anzuschauen, wieder aufgeschlüsselt nach den Sternen Kategorien. Dann untersuchen wir noch die Verteilung der Sterne, also wie viele Nachrichten gibt es von jeder Stern Kategorie. Dafür nutzen wir einen Countplot.

6. Nun erstellen wir einen neuen DataFrame, welcher uns die Durchschnittswerte der einzelnen Kategorien ausgibt. Auf das DataFrame wenden wir dann die Corr() Methode an, welche uns dann mögliche Korrelationen anzeigt. Dies visualisieren wir dann mit einer HeatMap, wodurch die Korrelationen deutlicher werden.

7. Damit können wir jetzt auch zum Natural Language Processing Teil übergehen. Dazu legen wir uns ein DataFrame an, welches nur die Spalten mit ein Stern und 5 Sternen bewerteten Nachrichten enthält. Dann legen wir noch zwei Objekte, X und Y an, welche die Text und Stern Spalten beinhalten. Nun benötigen wir einen weiteren Import, legen den CountVecorizer an und fitten diesen mit den X Daten.

8. Jetzt ist es wieder an der Zeit, die Daten in ein Trainings- und Testdatenset aufzuteilen. Dies machen wir wieder mit der Train_Test_Split Methode von Sklearn, welche wir davor importiert haben.

9. Dann gehen wir über und trainieren das Modell. Dafür importieren wir eine weitere Methode von Sklearn und wenden diese an. Im Anschluss fitten wir direkt unser neues Modell. Im nächsten Schritt führen wir die Prediction aus und um die Ergebnisse auszuwerten importieren wir wieder die Confusion_Matrix und den Calssification_Report. Diese zwei Auswertungswerkzeuge lassen wir uns auch direkt ausgeben. Dazu lässt sich sagen, dass die Ergebnisse schon sehr gut sind.

10. Jedoch im nächsten Schritt wenden wir noch das Text Processing an. Dazu importieren wir und wider zwei Klassen von SkLearn und erstellen uns eine Pipeline. Wir teilen wieder unsere Daten in ein Test- und Trainingsdatenset auf, trainieren die Pipeline, treffen die Prediction und lassen uns die Ergebnisse in  der Confusion_Matrix und dem Calssification_Report ausgeben. Im Vergleich zum ersten Ergebnis, welches nicht schlecht war, ist diese noch einmal besser und somit richtig gut.

Damit ist das Kapitel des Natural Language Processing abgeschlossen. Wir haben uns dafür die Daten genauer angeschaut mit der explorativen Datenanalyse. Dann haben wir unsere Daten vorbereitet und direkt die Modelle erstellt, trainiert, angewandt und zu guter letzt ausgewertet. Somit gehen wir weiter zum Thema Deep Learning .

