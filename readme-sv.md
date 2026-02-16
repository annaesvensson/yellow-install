# Install 0.9.8

Installera en helt ny webbplats. Utvecklad av Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Skärmdump" /></p>

## Hur man installerar en webbplats

[Följ installationsanvisningarna](https://datenstrom.se/sv/yellow/help/how-to-get-started). Du hälsas med ett hej, kan skapa ett [användarkonto](https://github.com/annaesvensson/yellow-edit/tree/main/readme-sv.md) och välja ett [språk](https://github.com/annaesvensson/yellow-language/tree/main/readme-sv.md). Dessutom kan du välja vilken typ av webbplats du vill göra. Alternativet `Liten webbsida` installerar endast de viktigaste funktionerna för små webbsidor. Alternativet `Liten wiki` installerar också [wiki-tillägget](https://github.com/annaesvensson/yellow-wiki/tree/main/readme-sv.md). Alternativet `Liten blogg` installerar också [blogg-tillägget](https://github.com/annaesvensson/yellow-wiki/tree/main/readme-sv.md). Du kan installera fler tillägg senare. Om problem uppstår under installationen visas ett felmeddelande och en länk till [felsökning](https://datenstrom.se/sv/yellow/help/troubleshooting).

## Hur man hoppar över installationen

Du kan hoppa över installationen på [kommandoraden](https://github.com/annaesvensson/yellow-core/tree/main/readme-sv.md). Öppna ett terminalfönster. Detta är praktiskt för utvecklare som vill köra systemtester. Gå till installationsmappen där filen `yellow.php` finns. Skriv `php yellow.php skip installation` följt av ett alternativ. Alternativet `small` installerar bara de viktigaste sakerna för små webbsidor, detta är samma som standardinstallationen. Alternativet `medium` installerar [hjälp-tillägget](https://github.com/annaesvensson/yellow-help/tree/main/readme-sv.md) tillsammans med rekommenderade tillägg. Alternativet `large` installerar alla [tillägg på officiella webbplatsen](https://datenstrom.se/sv/yellow/extensions/).

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
