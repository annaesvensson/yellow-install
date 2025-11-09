<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.9.5

Eine brandneue Webseite installieren.

<p align="center"><img src="SCREENSHOT.png" alt="Bildschirmfoto"></p>

## Wie man eine Webseite installiert

Datenstrom Yellow herunterladen und der Installationsanleitung folgen. Das Installationsprogramm hilft dir beim Einrichten deiner Webseite und stellt sicher dass alle Installationsanforderungen erfüllt sind. Falls Problem während der Installation auftreten, dann zeigt deine Webseite eine Fehlermeldung und einen Link zur [Fehlerbehebung](https://datenstrom.se/de/yellow/help/troubleshooting) an. Aber auf den meisten Webservern ist deine Webseite sofort erreichbar. Die wichtigsten Dinge sind mit dabei. [Loslegen](https://datenstrom.se/de/yellow/help/how-to-get-started).

## Wie man die Installation überspringt

Du kannst die Installation in der [Befehlszeile](https://github.com/annaesvensson/yellow-core/tree/main/README-de.md) überspringen. Öffne ein Terminalfenster. Gehe ins Installations-Verzeichnis, dort wo sich die Datei `yellow.php` befindet. Gib ein `php yellow.php skip installation` gefolgt von einer Option. Die Option `small` installiert nur die wichtigsten Dinge für kleine Webseiten, das ist dasselbe wie die Standardinstallation mit der englischen Sprache. Die Option `medium` installiert die [Hilfe-Erweiterung](https://github.com/annaesvensson/yellow-help/tree/main/README-de.md) zusammen mit empfohlenen Erweiterungen, das ist praktisch wenn man die Hilfe verbessern möchte. Die Option `large` installiert alle verfügbaren Erweiterungen, das ist praktisch wenn man Systemtests durchführen möchte.

## Beispiele

Installation in der Befehlszeile überspringen:

`php yellow.php skip installation`  

Installation in der Befehlszeile überspringen, verschiedene Optionen:

`php yellow.php skip installation small`  
`php yellow.php skip installation medium`  
`php yellow.php skip installation large`  

## Einstellungen

Die folgenden Dateien werden bei der Installation geändert:

`system/extensions/yellow-system.ini` = Datei mit Systemeinstellungen  
`system/extensions/yellow-language.ini` = Datei mit Spracheinstellungen  
`system/extensions/yellow-user.ini` = Datei mit Benutzereinstellungen  
`system/extensions/yellow-website.log` = Logdatei der Webseite  

Die folgenden Dateien werden bei der Installation angepasst:

`content/1-home/page.md` = Inhaltsdatei für die Startseite  
`content/9-about/page.md` = Inhaltsdatei für die Informationsseite  
`content/shared/page-new-default.md` = Inhaltsdatei für neue Seite  
`content/shared/page-new-wiki.md` = Inhaltsdatei für neue Wikiseite, [falls Wiki ausgewählt wurde](https://github.com/annaesvensson/yellow-wiki/tree/main/README-de.md)  
`content/shared/page-new-blog.md` = Inhaltsdatei für neue Blogseite, [falls Blog ausgewählt wurde](https://github.com/annaesvensson/yellow-blog/tree/main/README-de.md)  
`content/shared/page-error-404.md` = Inhaltsdatei für Fehlerseite  

## Entwickler

Anna Svensson. [Hilfe finden](https://datenstrom.se/de/yellow/help/).
