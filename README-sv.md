<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.9.4

Installera en helt ny webbplats.

<p align="center"><img src="SCREENSHOT.png" alt="Skärmdump"></p>

## Hur man installerar en webbplats

Ladda ner Datenstrom Yellow och följ installationsanvisningarna. Installationsprogrammet hjälper dig att inreda din webbplats och säkerställer att alla installationskrav har uppfyllts. Din webbplats är tillgänglig omedelbart. De viktigaste sakerna ingår. Du kan lägga till fler funktioner senare. Det finns tillägg med ytterligare funktioner, språk och teman som du kan installera. [Komma igång](https://datenstrom.se/sv/yellow/help/how-to-get-started).

## Hur man hoppar över installationen

Du kan hoppa över installationen på [kommandoraden](https://github.com/annaesvensson/yellow-core/tree/main/README-sv.md). Öppna ett terminalfönster. Gå till installationsmappen där filen `yellow.php` finns. Skriv `php yellow.php skip installation` följt av ett alternativ. Alternativet `small` installerar bara de viktigaste sakerna för små webbsidor, detta är samma som standardinstallationen på engelska. Alternativet `medium` installerar även [hjälp-tillägget](https://github.com/annaesvensson/yellow-help/tree/main/README-sv.md), detta är praktiskt om man vill prova vissa funktioner. Alternativet `large` installerar alla tillgängliga tillägg.

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
`system/extensions/yellow-extension.ini` = fil med tilläggsinställningar  
`system/extensions/yellow-website.log` = loggfilen för webbplatsen  

Följande filer kommer att anpassas under installationen:

`content/1-home/page.md` = innehållsfil för hemsidan  
`content/9-about/page.md` = innehållsfil för informationssidan  
`content/shared/page-new-default.md` = innehållsfil för ny sida  
`content/shared/page-new-wiki.md` = innehållsfil för ny wikisida, [om wiki valdes](https://github.com/annaesvensson/yellow-wiki/tree/main/README-sv.md)  
`content/shared/page-new-blog.md` = innehållsfil för ny bloggsida, [om blogg valdes](https://github.com/annaesvensson/yellow-blog/tree/main/README-sv.md)  
`content/shared/page-error-404.md` = innehållsfil för felsidan  

## Tack

Detta tillägg innehåller [översättningar](https://github.com/annaesvensson/yellow-language/tree/main/README-sv.md) av olika bidragsgivare. Tack för ett bra jobb.

## Developer

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
