# Digitales Bremen

## Zur Geschichte

Jede Woche stelle ich mir Sonntags die Frage: _Welche Tonnen muss ich an die Straße stellen_? Ich merke mir selten, 
welche Tonnen letzte Woche dran waren.  

Natürlich gibt es für das Problem diverse Lösungen

* Müllkalender aufhängen
* Magnete verwenden
* Nachbarn überwachen
* Manuell Termin in meinen digitalen Kalender eintragen

Das sind alles Lösungen, die meine Anforderungen nicht erfüllen. Ich möchte an den Abholtermin aktiv erinnert werden und 
zugleich auch wissen wollen, um welche Abholung es sich handelt.

Da es das für Bremen in dieser Art nicht gibt und ich immer auf der Suche nach kleinen überschaubaren Problemen bin, um 
neue Technologien und Praktiken kennen zu lernen, entstand das erste Projekt.

Ich bin an Kritik, Verbesserungsvorschlägen und Unterstützung interessiert! 

## Projekte

Hier findet sich die Liste der aktuellen Projekte und des jeweiligen Zustands. 

### Muellsammler

Ein in [GO](https://golang.org/) entwickeltes Programm, welches die von der 
[Bremer Stadtreinigung](https://www.die-bremer-stadtreinigung.de/) bereitgestellten Webseite nach allen Abholdaten aller
Bremer Adressen durchsucht und regelmäßig eine entsprechende Datei im JSON Format bereitstellt. 

URL | Stand | Sonstiges
--- | --- | ---
[github](https://github.com/digitalesbremen/muellsammler) | Produktiv | Läuft aktuell einmal in der Woche

### Muelltermine

Ein in [GO](https://golang.org/) entwickeltes Programm, welches ermöglicht, die eigene Straße zu suchen und die
Termine in den eigenen Kalender zu importieren.

URL | Stand | Sonstiges
--- | --- | ---
[github](https://github.com/digitalesbremen/muelltermine) | Sehr frühes Stadium | Lädt bisher nur die vom Muellsammler erzeugten Daten in den Speicher