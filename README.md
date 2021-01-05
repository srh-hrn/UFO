# UFO

Hallo :)
Hier ein kurzer Überblick zu meinem Projekt:

Den Schaltkreis habe ich bereits ausprobiert und schon ein bisschen gelötet und er funktioniert soweit sehr gut. Ein Video davon habe ich im Wiki hochgeladen.

Folgende 20 Fehler treten momentan im DRC auf:

1 - 7 Clearance Violation: bei Durchkontaktierungen für LEDs auf Fcu, allerdings nicht bei allen. Manche konnte ich durch Verschieben in Millimeterschritten korrigieren. Ich werde versuchen, die restlichen Fehler genauso zu beseitigen, aber wahrscheinlich schränken diese die Funktion des PCBs gar nicht ein.

8 - 19 Footprint has malformed courtyard (not a closed shape): Dieser Fehler tritt an mehreren Stellen eines Footprints auf, den ich in der library gefunden habe. Zoomt man an die markierten Stellen dich heran, sind kleine Ausbuchtungen der geraden Linien zu erkennen. Die Zeichnung ist also lediglich nicht ganz sauber, der Footprint jedoch vollständig und geschlossen.

20 Silkscreen clipped by solder mask: Das betrifft eine kleine Stelle am Ufo. Ich habe dort eine Weile ausprobiert, wie ich die Linien ziehe, damit sie zwar geschlossen sind, aber nichts überschneiden. Letztendlich gibt es einen Berührungspunkt, da die Linie abgerundet ist, aber ich denke, das sollte kein Problem sein.


Danke fürs Drüberschauen!
