# Install 0.9.7

Installera en helt ny webbplats. Utvecklad av Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Skärmdump"></p>

## Hur man installerar en webbplats

Ladda ner Datenstrom Yellow och följ installationsanvisningarna. Installationsprogrammet hjälper dig att inreda din webbplats och säkerställer att alla installationskrav har uppfyllts. Om problem uppstår under installationen kommer din webbplats att visa ett felmeddelande och en länk till [felsökning](https://datenstrom.se/sv/yellow/help/troubleshooting). Men på de flesta webbservrar kommer din webbplats att vara omedelbart tillgänglig. De viktigaste sakerna ingår. [Komma igång](https://datenstrom.se/sv/yellow/help/how-to-get-started).

## Hur man hoppar över installationen

Du kan hoppa över installationen på [kommandoraden](https://github.com/annaesvensson/yellow-core/tree/main/readme-sv.md). Öppna ett terminalfönster. Gå till installationsmappen där filen `yellow.php` finns. Skriv `php yellow.php skip installation` följt av ett alternativ. Alternativet `small` installerar bara de viktigaste sakerna för små webbsidor, detta är samma som standardinstallationen på engelska. Alternativet `medium` installerar [hjälp-tillägget](https://github.com/annaesvensson/yellow-help/tree/main/readme-sv.md) tillsammans med rekommenderade tillägg, detta är praktiskt om man vill göra prestandatestning. Alternativet `large` installerar alla tillgängliga tillägg, detta är praktiskt om man vill köra systemtester.

## Exempel

Hoppa över installationen på kommandoraden:

`php yellow.php skip installation`  

Hoppa över installationen på kommandoraden, olika alternativ:

`php yellow.php skip installation small`  
`php yellow.php skip installation medium`  
`php yellow.php skip installation large`  

## Inställningar

Följande filer kommer att ändras under installationen:

`system/extensions/yellow-system.ini` = fil med systeminställningar  
`system/extensions/yellow-language.ini` = fil med språkinställningar  
`system/extensions/yellow-user.ini` = fil med användarinställningar  
`system/extensions/yellow-website.log` = webbplatsens loggfil  

Följande filer kommer att anpassas under installationen:

`content/1-home/page.md` = innehållsfil för hemsidan  
`content/9-about/page.md` = innehållsfil för informationssidan  
`content/shared/page-new-default.md` = innehållsfil för ny sida  
`content/shared/page-new-wiki.md` = innehållsfil för ny wikisida, [om wiki valdes](https://github.com/annaesvensson/yellow-wiki/tree/main/readme-sv.md)  
`content/shared/page-new-blog.md` = innehållsfil för ny bloggsida, [om blogg valdes](https://github.com/annaesvensson/yellow-blog/tree/main/readme-sv.md)  
`content/shared/page-error-404.md` = innehållsfil för felsidan  

Har du några frågor? [Få hjälp](https://datenstrom.se/sv/yellow/help/).
