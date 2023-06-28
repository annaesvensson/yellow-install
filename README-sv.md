<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.90

Installera en helt ny webbplats.

<p align="center"><img src="install-screenshot.png?raw=true" alt="Skärmdump"></p>

## Hur man installerar en webbplats

För att installera packa upp en fil och du är redo att gå. Först kontrollerar installationsprogrammet om alla krav har uppfyllts, till exempel om din webbserver fungerar som den ska. Sedan hjälper installationsprogrammet dig att inreda din webbplats. Ange ditt namn, email och lösenord. Välj vad du vill göra och klicka på `Installera`. När installationsprogrammet har gjort sitt arbete kommer det att ta bort sig själv. [Läs mer om installation](https://datenstrom.se/sv/yellow/help/how-to-get-started).

Om du vill lägga till funktioner, språk och teman, det finns [tillägg](https://github.com/datenstrom/yellow-extensions/tree/main/README-sv.md) och ett [API för utvecklare](https://datenstrom.se/sv/yellow/help/api-for-developers).

## Inställningar

Följande filer kommer att anpassas under installationen:

`content/1-home/page.md` = innehållsfil för hemsidan  
`content/9-about/page.md` = innehållsfil för informationssidan  
`content/shared/page-new-default.md` = innehållsfil för ny sida  
`content/shared/page-new-wiki.md` = innehållsfil för ny wikisida  
`content/shared/page-new-blog.md` = innehållsfil för ny bloggsida  
`content/shared/page-error-404.md` = innehållsfil för felsidan  
`system/extensions/yellow-system.ini` = fil med systeminställningar  
`system/extensions/yellow-language.ini` = fil med språkinställningar  
`system/extensions/yellow-user.ini` = fil med användarinställningar  

Loggfilen finns i filen `system/extensions/yellow-website.log`.

## Tack

Detta tillägg innehåller [översättningar av olika bidragsgivare](https://github.com/annaesvensson/yellow-language/graphs/contributors). Tack för ett bra jobb.

## Developer

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
