# Install 0.9.8

Eine brandneue Webseite installieren. Entwickelt von Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Bildschirmfoto"></p>

## Wie man eine Webseite installiert

[Folge der Installationsanleitung](https://datenstrom.se/de/yellow/help/how-to-get-started). Du wirst mit einem Hallo begrüßt, kannst ein [Benutzerkonto](https://github.com/annaesvensson/yellow-edit/tree/main/readme-de.md) erstellen und eine [Sprache](https://github.com/annaesvensson/yellow-language/tree/main/readme-de.md) auswählen. Darüber hinaus kannst du auswählen welche Art von Webseite du machen möchtest. Die Option `Kleine Webseite` installiert nur die wichtigsten Dinge für kleine Webseiten. Die Option `Kleines Wiki` installiert zusätzlich noch die [Wiki-Erweiterung](https://github.com/annaesvensson/yellow-wiki/tree/main/readme-de.md). Die Option `Kleines Blog` installiert zusätzlich noch die [Blog-Erweiterung](https://github.com/annaesvensson/yellow-blog/tree/main/readme-de.md). Du kannst später weitere Funktionen hinzufügen. Es gibt Erweiterungen mit zusätzlichen Funktionen, Sprachen und Themes die du installieren kannst. Das Installationsprogramm hilft dir beim Einrichten deiner Webseite und stellt sicher dass alle Installationsanforderungen erfüllt sind. Falls Probleme während der Installation auftreten, dann wird eine Fehlermeldung und einen Link zur [Fehlerbehebung](https://datenstrom.se/de/yellow/help/troubleshooting) angezeigt.

## Wie man die Installation überspringt

Du kannst die Installation in der [Befehlszeile](https://github.com/annaesvensson/yellow-core/tree/main/readme-de.md) überspringen. Öffne ein Terminalfenster. Gehe ins Installations-Verzeichnis, dort wo sich die Datei `yellow.php` befindet. Gib ein `php yellow.php skip installation` gefolgt von einer Option. Die Option `small` installiert nur die wichtigsten Dinge für kleine Webseiten, das ist dasselbe wie die Standardinstallation mit der englischen Sprache. Die Option `medium` installiert die [Hilfe-Erweiterung](https://github.com/annaesvensson/yellow-help/tree/main/readme-de.md) zusammen mit empfohlenen Erweiterungen, das ist praktisch wenn man Leistungstests machen möchte. Die Option `large` installiert alle verfügbaren Erweiterungen, das ist praktisch wenn man Systemtests durchführen möchte.

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
`content/shared/page-new-wiki.md` = Inhaltsdatei für neue Wikiseite, [falls Wiki ausgewählt wurde](https://github.com/annaesvensson/yellow-wiki/tree/main/readme-de.md)  
`content/shared/page-new-blog.md` = Inhaltsdatei für neue Blogseite, [falls Blog ausgewählt wurde](https://github.com/annaesvensson/yellow-blog/tree/main/readme-de.md)  
`content/shared/page-error-404.md` = Inhaltsdatei für Fehlerseite  

Hast du Fragen? [Hilfe finden](https://datenstrom.se/de/yellow/help/).
