Allgemein:
Die App stellt die Umsetztung der bereits letzten Semester vorangegengen Planung durch das Fach DPDD da. Ihre Funktion ist als Hilfsmittel beim Pathfinder Rollenspiel gedacht.

Grundfunktionen:
Im Minimal Valuable Produkt sind Folgende Kernfunktionen enthalten:
-Erstellung eines neuen Charakters mit Schritt für Schritt Hilfe
  -Klassenauswahl
  -Rassenauswahl
  -Attributswertermittlung mit passenden Modifikatoren
  -Punktkaufmöglichkeit der Attributswertermittlung
  -Geschlechtswahl, Heimatswahl, Sonstige Detaileingaben
  -Verrechnung des Alters
  -Klassenangepasste Gesinnungswahl  
  -Charakterangepasste Götterwahl
  -Speichern der Charakterwerte
  -Ausgabe der Charakterwerte
  -Hilfstexte (i) für ein besseres Verständnis

Designidee:
Das Design ist vor allem in den Farben des Pathfindergrundregelwerks gehalten. Dieses Farbschema sollte sich einheitlich durch die Komplette App ziehen. Ein papierhafter Hintergrund wurde gewählt, um den Benutzer gleich einen vertrauten Bezug auf die neue Form des Charakterbogens zu geben. Der Startbildschirm zeigt ein handlungsstarkes Bild, um auf das eigentliche Spielen einzustimmen. Die Anfangsbuchstaben des Namens haben sich als Logo durchgesetzt in einer Schrift, die dem klassischen Pathfinderschriftzug sehr nahe kommt. Das Logo wurde in leicht abgewandelter Form auch als Ladebildschirm verwendet.

Erweiterbarkeit:
Das Design und das Layout wurde sehr erweiterbar gehalten, da wir noch ein enorm großes Maß an Funktionen einarbeiten wollen. Vorerst behalten wir die Charaktererschaffung im Auge, weshalb der Fortschrittsbalken aktuell noch von 40% auf 90% springt. Und diese neuen Eingaben müssen selbstverständlich auch noch in der Charakteranzeige präsentiert werden können. Diese ist durch das hinzufügen weiterer Schaltflächen noch sehr weit vergrößerbar. Auch sollen noch Funktionen folgen, die nicht als Vorbereitung des Spiels sondern als Hilfe während des Spiels gelten. So zum Beispiel die dynamische Anpassung der Statuswerte oder die Berechnung der aktuellen Traglast.

Speicherfunktion:
Zum realisieren der Charakterspeicherung wurde der binary Formatter des .Net Frameworks verwendet um eine serialisierbare Klasse ein- und auszulesen. Diese ist sehr einfach erweiterbar ohne dabei vorherige Versionen zunichte zu machen und zugleich aber für den Benutzer nicht manipulierbar.

Datenbankzugriff:
Durch das bereits häufige auftreten von kleinen Datenbankstrukturen im Code (vor allem durch Switches) wurde schnell klar, dass die zuweisbaren Datenwerte in eine Datenbank ausgelagert werden sollten. Die Klasse InfoText.cs stellt eine vorübergehende Lösung da, weil der Aufwand im Rahmen der Studienarbeit als zu groß erachtet wurde. Es gibt viele Stellen im Code die von einer eingepflegten Datenbank profitieren könnten.

Cross-Plattform:
Das Projekt wurde mit Xamarin unter Visual Studio durchgeführt in der Hoffnung später auch auf anderen Plattformen veröffentlichen zu können. Als Programmiersprache diente C#. Als Grundlage wurde iOS verwendet, da von uns, wie bereits beschrieben, die Benutzbarkeit priorisiert wurde. Wir müssen leider gestehen uns mit dem Projekt übernommen zu haben und hatten daher keine Zeit mehr für eine Androidumsetzung, dem eigentlichen Thema der Studienarbeit.

Responsive Design:
Hier folgt eine weitere Schwachstelle der Applikation. Durch einen fehlenden Button in der Visual Studio Community Edition ist es seit Ende 2017 nur noch per Code möglich das Interface skalieren zu lassen. Da wir aber den Code möglichst frei halten wollten von betriebsystemabhänigen Zeilen wollten wir das Interface größtenteils durch die Storyboarddatei verwalten. Diese kann aktuell aber leider nur konstante Breiten und Höhen für Buttons und Label vergeben. Daher ist die Benutzbarkeit auf kleineren Geräten (iPhone 5S, iPhone SE) eingeschränkt und auf den iPads ist der größte Teil des Bildschirms unbenutzt. Trotzdem haben wir unser bestmögliches gegeben um ein halbwegs skalierendes Interface zu erstellen.

Abschluss:
Im ganzen kann man sagen das wir uns ganz schön übernommen und verrannt haben, aber trotzdem sehr stolz auf unser Produkt sind. Wir haben enorm viel dazugelernt und jede Menge Hinternisse überwunden. Und es werden noch wesentlich mehr auf uns zukommen. Wir haben viel Schweiß und Herzblut in diese Anwendung gesteckt und dürfen stolz verkünden, dass sie bereits von Nutzen gewesen ist.

Nicole Ebert -  Mat.Nr.00123380
Nicklas Ebert - Mat.Nr.00123732