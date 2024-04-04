<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.9.1

Eine brandneue Webseite installieren.

<p align="center"><img src="SCREENSHOT.png" alt="Bildschirmfoto"></p>

## Wie man eine Webseite installiert

Datenstrom Yellow herunterladen und der Installationsanleitung folgen. Das Installationsprogramm hilft dir beim Einrichten deiner Webseite und stellt sicher dass alle Installationsanforderungen erfüllt sind. Deine Webseite ist sofort erreichbar. Die wichtigsten Dinge für kleine Webseiten sind mit dabei. Du kannst Funktionen, Sprachen und Themes hinzufügen. [Loslegen](https://datenstrom.se/de/yellow/help/how-to-get-started).

Wenn du die Installation in der [Befehlszeile](https://github.com/annaesvensson/yellow-core/tree/main/README-de.md) überspringen möchtest, kannst du `php yellow.php skip installation` eingeben.

## Wie man eine Webseite deinstalliert

Lösche alle Dateien im Installationsverzeichnis.

## Beispiele

Installation in der Befehlszeile überspringen, nur die wichtigsten Erweiterungen installieren:

`php yellow.php skip installation small`  

Installation in der Befehlszeile überspringen, beinhaltet die [Help-Erweiterung](https://github.com/annaesvensson/yellow-help/tree/main/README-de.md):

`php yellow.php skip installation medium`  

Installation in der Befehlszeile überspringen, beinhaltet alle [vorhandenen Erweiterungen](https://datenstrom.se/de/yellow/extensions/):

`php yellow.php skip installation large`  

## Einstellungen

Die folgenden Dateien werden bei der Installation geändert:

`system/extensions/yellow-system.ini` = Datei mit Systemeinstellungen  
`system/extensions/yellow-language.ini` = Datei mit Spracheinstellungen  
`system/extensions/yellow-user.ini` = Datei mit Benutzereinstellungen  
`system/extensions/yellow-extension.ini` = Datei mit Erweiterungseinstellungen  

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
