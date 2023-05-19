<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.89

Install a brand new, shiny website.

<p align="center"><img src="install-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install a website

Installing is unzipping one file and you are ready to go. First the installer checks whether all requirements have been met, for example whether your web server is working properly. Then the installer helps you with setting up your website. Enter your name, email and password. Select what you want to do and click `Install`. After the installer has done its work it will delete itself. [Learn more about installation](https://datenstrom.se/yellow/help/how-to-get-started).

## Settings

The following files will be customised during installation:

`content/1-home/page.md` = content file for home page  
`content/9-about/page.md` = content file for information page  
`content/shared/page-new-default.md` = content file for new page  
`content/shared/page-new-wiki.md` = content file for new wiki page  
`content/shared/page-new-blog.md` = content file for new blog page  
`content/shared/page-error-404.md` = content file for error page  
`system/extensions/yellow-system.ini` = file with system settings  
`system/extensions/yellow-language.ini` = file with language settings  
`system/extensions/yellow-user.ini` = file with user settings  

The log file can be found in file `system/extensions/yellow-website.log`.

## Acknowledgements

This extension includes [translations by various contributors](https://github.com/annaesvensson/yellow-language/graphs/contributors). Thank you for the good work.

## Developer

Anna Svensson. [Get help](https://datenstrom.se/yellow/help/).
