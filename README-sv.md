<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.94

Installera en helt ny webbplats.

<p align="center"><img src="SCREENSHOT.png" alt="Skärmdump"></p>

## Hur man installerar en webbplats

Ladda ner Datenstrom Yellow och följ installationsanvisningarna. Installationsprogrammet hjälper dig att inreda din webbplats och säkerställer att alla installationskrav har uppfyllts. Din webbplats är tillgänglig omedelbart. De viktigaste sakerna för små webbsidor ingår i installationen. Du kan lägga till funktioner, språk och teman. [Komma igång](https://datenstrom.se/sv/yellow/help/how-to-get-started).

Om du vill hoppa över installationen på [kommandoraden](https://github.com/annaesvensson/yellow-core/tree/main/README-sv.md), skriv `php yellow.php skip installation`.

## Hur man avinstallerar en webbplats

Ta bort alla filer i installationsmappen.

## Exempel

Hoppa över installationen på kommandoraden, installera endast de viktigaste tilläggen:

`php yellow.php skip installation`  

Hoppa över installationen på kommandoraden, installera maximalt antal tillägg:

`php yellow.php skip installation maximal`  

Hoppa över installationen på kommandoraden, installera minimalt antal tillägg:

`php yellow.php skip installation minimal`  

## Inställningar

Följande filer kommer att ändras under installationen:

`system/extensions/yellow-system.ini` = fil med systeminställningar  
`system/extensions/yellow-language.ini` = fil med språkinställningar  
`system/extensions/yellow-user.ini` = fil med användarinställningar  

Följande filer kommer att anpassas under installationen:

`content/1-home/page.md` = innehållsfil för hemsidan  
`content/9-about/page.md` = innehållsfil för informationssidan  
`content/shared/page-new-default.md` = innehållsfil för ny sida  
`content/shared/page-new-wiki.md` = innehållsfil för ny wikisida, [om wiki valdes](https://github.com/annaesvensson/yellow-wiki/tree/main/README-sv.md)  
`content/shared/page-new-blog.md` = innehållsfil för ny bloggsida, [om blogg valdes](https://github.com/annaesvensson/yellow-blog/tree/main/README-sv.md)  
`content/shared/page-error-404.md` = innehållsfil för felsidan  

Loggfilen finns i filen `system/extensions/yellow-website.log`.

## Tack

Detta tillägg innehåller [översättningar](https://github.com/annaesvensson/yellow-language/tree/main/README-sv.md) av olika bidragsgivare. Tack för ett bra jobb.

## Developer

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
