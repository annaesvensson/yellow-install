<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.90

Eine brandneue Webseite installieren.

<p align="center"><img src="install-screenshot.png?raw=true" alt="Bildschirmfoto"></p>

## Wie man eine Webseite installiert

[Folge der Installationsanleitung](https://datenstrom.se/de/yellow/help/how-to-get-started). Zuerst überprüft das Installationsprogramm ob alle Anforderungen erfüllt sind, zum Beispiel ob dein Webserver richtig funktioniert. Dann hilft dir das Installationsprogramm beim Einrichten deiner Webseite. Gebe deinen Namen, E-Mail und Kennwort ein. Wähle aus was du machen willst und klicke auf `Installieren`. Nachdem das Installationsprogramm seine Arbeit erledigt hat löscht es sich von selbst. Deine Webseite ist sofort erreichbar. Die wichtigsten Dinge für kleine Webseiten sind mit dabei. Du kannst Funktionen, Sprachen und Themes hinzufügen. Es gibt [Erweiterungen](https://github.com/datenstrom/yellow-extensions/tree/main/README-de.md) und eine [API für Entwickler](https://datenstrom.se/de/yellow/help/api-for-developers).

## Einstellungen

Die folgenden Einstellungen werden bei der Installation konfiguriert:

`system/extensions/yellow-system.ini` = Datei mit Systemeinstellungen  
`system/extensions/yellow-language.ini` = Datei mit Spracheinstellungen  
`system/extensions/yellow-user.ini` = Datei mit Benutzereinstellungen  

Die folgenden Dateien werden bei der Installation angepasst:

`content/1-home/page.md` = Inhaltsdatei für die Startseite  
`content/9-about/page.md` = Inhaltsdatei für die Informationsseite  
`content/shared/page-new-default.md` = Inhaltsdatei für neue Seite  
`content/shared/page-new-wiki.md` = Inhaltsdatei für neue Wikiseite  
`content/shared/page-new-blog.md` = Inhaltsdatei für neue Blogseite  
`content/shared/page-error-404.md` = Inhaltsdatei für Fehlerseite  

Die Logdatei findet man in der Datei `system/extensions/yellow-website.log`.

## Danksagung

Diese Erweiterung enthält [Übersetzungen](https://github.com/annaesvensson/yellow-language/tree/main/README-de.md) von verschiedenen Mitwirkenden. Danke für die gute Arbeit.

## Entwickler

Anna Svensson. [Hilfe finden](https://datenstrom.se/de/yellow/help/).
