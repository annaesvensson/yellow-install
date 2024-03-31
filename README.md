<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.94

Install a brand new website.

<p align="center"><img src="SCREENSHOT.png" alt="Screenshot"></p>

## How to install a website

Download Datenstrom Yellow and follow the installation instructions. The installer helps you with setting up your website and makes sure all installation requirements have been met. Your website is immediately available. The most important things for small websites are included. You can add features, languages and themes. [Get started](https://datenstrom.se/yellow/help/how-to-get-started).

If you want to skip the installation at the [command line](https://github.com/annaesvensson/yellow-core), type `php yellow.php skip installation`.

## How to uninstall a website

Delete all files in the installation folder.

## Examples

Skipping the installation at the command line, install only the most important things:

`php yellow.php skip installation small`  

Skipping the installation at the command line, install also the [help extension](https://github.com/annaesvensson/yellow-help):

`php yellow.php skip installation medium`  

Skipping the installation at the command line, install all the [available extensions](https://datenstrom.se/yellow/extensions/):

`php yellow.php skip installation large`  

## Settings

The following files will be modified during the installation:

`system/extensions/yellow-system.ini` = file with system settings  
`system/extensions/yellow-language.ini` = file with language settings  
`system/extensions/yellow-user.ini` = file with user settings  

The following files will be customised during the installation:

`content/1-home/page.md` = content file for home page  
`content/9-about/page.md` = content file for information page  
`content/shared/page-new-default.md` = content file for new page  
`content/shared/page-new-wiki.md` = content file for new wiki page, [if wiki was selected](https://github.com/annaesvensson/yellow-wiki)  
`content/shared/page-new-blog.md` = content file for new blog page, [if blog was selected](https://github.com/annaesvensson/yellow-blog)  
`content/shared/page-error-404.md` = content file for error page  

The log file can be found in file `system/extensions/yellow-website.log`.

## Acknowledgements

This extension includes [translations](https://github.com/annaesvensson/yellow-language) by various contributors. Thank you for the good work.

## Developer

Anna Svensson. [Get help](https://datenstrom.se/yellow/help/).
