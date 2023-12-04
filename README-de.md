<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.93

Eine brandneue Webseite installieren.

<p align="center"><img src="SCREENSHOT.png?raw=true" alt="Bildschirmfoto"></p>

## Wie man eine Webseite installiert

Datenstrom Yellow herunterladen und der Installationsanleitung folgen. Das Installationsprogramm hilft dir beim Einrichten deiner Webseite und überprüft ob alle Installationsanforderungen erfüllt sind. Deine Webseite ist sofort erreichbar. Die wichtigsten Dinge für kleine Webseiten sind mit dabei. Du kannst Funktionen, Sprachen und Themes hinzufügen. [Loslegen](https://datenstrom.se/de/yellow/help/how-to-get-started).

Wenn du die Installation in der [Befehlszeile](https://github.com/annaesvensson/yellow-core/tree/main/README-de.md) überspringen möchtest, kannst du `php yellow.php skip installation` eingeben.

## Wie man eine Webseite deinstalliert

Lösche alle Dateien im Installationsverzeichnis.

## Beispiele

Installation in der Befehlszeile überspringen:

`php yellow.php skip installation`  

Installation in der Befehlszeile überspringen, maximale Anzahl an Erweiterungen installieren:

`php yellow.php skip installation maximal`  

Installation in der Befehlszeile überspringen, minimale Anzahl an Erweiterungen installieren:

`php yellow.php skip installation minimal`  

## Einstellungen

Die folgenden Einstellungen werden bei der Installation konfiguriert:

`system/extensions/yellow-system.ini` = Datei mit Systemeinstellungen  
`system/extensions/yellow-language.ini` = Datei mit Spracheinstellungen  
`system/extensions/yellow-user.ini` = Datei mit Benutzereinstellungen  

Die folgenden Dateien werden bei der Installation angepasst:

`content/1-home/page.md` = Inhaltsdatei für die Startseite  
`content/9-about/page.md` = Inhaltsdatei für die Informationsseite  
`content/shared/page-new-default.md` = Inhaltsdatei für neue Seite  
`content/shared/page-new-wiki.md` = Inhaltsdatei für neue Wikiseite, [falls Wiki ausgewählt wurde](https://github.com/annaesvensson/yellow-wiki/tree/main/README-de.md)  
`content/shared/page-new-blog.md` = Inhaltsdatei für neue Blogseite, [falls Blog ausgewählt wurde](https://github.com/annaesvensson/yellow-blog/tree/main/README-de.md)  
`content/shared/page-error-404.md` = Inhaltsdatei für Fehlerseite  

Die Logdatei findet man in der Datei `system/extensions/yellow-website.log`.

## Danksagung

Diese Erweiterung enthält [Übersetzungen](https://github.com/annaesvensson/yellow-language/tree/main/README-de.md) von verschiedenen Mitwirkenden. Danke für die gute Arbeit.

## Entwickler

Anna Svensson. [Hilfe finden](https://datenstrom.se/de/yellow/help/).
