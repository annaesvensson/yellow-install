<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.90

Installera en helt ny webbplats.

<p align="center"><img src="install-screenshot.png?raw=true" alt="Skärmdump"></p>

## Hur man installerar en webbplats

[Följ installationsanvisningarna](https://datenstrom.se/sv/yellow/help/how-to-get-started). Först kontrollerar installationsprogrammet om alla krav har uppfyllts, till exempel om din webbserver fungerar som den ska. Sedan hjälper installationsprogrammet dig att inreda din webbplats. Ange ditt namn, email och lösenord. Välj vad du vill göra och klicka på `Installera`. När installationsprogrammet har gjort sitt arbete kommer det att ta bort sig själv. Din webbplats är tillgänglig omedelbart. De viktigaste sakerna för små webbsidor ingår. Du kan lägga till funktioner, språk och teman. Det finns [tillägg](https://github.com/datenstrom/yellow-extensions/tree/main/README-sv.md) och ett [API för utvecklare](https://datenstrom.se/sv/yellow/help/api-for-developers).

## Inställningar

Följande inställningar kommer att konfigureras under installationen:

`system/extensions/yellow-system.ini` = fil med systeminställningar  
`system/extensions/yellow-language.ini` = fil med språkinställningar  
`system/extensions/yellow-user.ini` = fil med användarinställningar  

Följande filer kommer att anpassas under installationen:

`content/1-home/page.md` = innehållsfil för hemsidan  
`content/9-about/page.md` = innehållsfil för informationssidan  
`content/shared/page-new-default.md` = innehållsfil för ny sida  
`content/shared/page-new-wiki.md` = innehållsfil för ny wikisida  
`content/shared/page-new-blog.md` = innehållsfil för ny bloggsida  
`content/shared/page-error-404.md` = innehållsfil för felsidan  

Loggfilen finns i filen `system/extensions/yellow-website.log`.

## Tack

Detta tillägg innehåller [översättningar](https://github.com/annaesvensson/yellow-language/tree/main/README-sv.md) av olika bidragsgivare. Tack för ett bra jobb.

## Developer

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
