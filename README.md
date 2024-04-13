<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.9.4

Install a brand new website.

<p align="center"><img src="SCREENSHOT.png" alt="Screenshot"></p>

## How to install a website

Download Datenstrom Yellow and follow the installation instructions. The installer helps you with setting up your website and makes sure all installation requirements have been met. Your website is immediately available. The most important things are included. Of course you can change this later. There are extensions with additional features, languages and themes that you can install. [Get started](https://datenstrom.se/yellow/help/how-to-get-started).

## How to skip the installaton

You can skip the installation at the [command line](https://github.com/annaesvensson/yellow-core). Open a terminal window. Go to your installation folder, where the file `yellow.php` is. Type `php yellow.php skip installation` followed by an option. The `small` option installs only the most important things for small websites, this is the same as the standard installation with the English language. The `medium` option installs also the help extension with the documentation. The `large` option installs all available extensions.

## Examples

Skipping the installation at the command line:

`php yellow.php skip installation`  

Skipping the installation at the command line, different options:

`php yellow.php skip installation small`  
`php yellow.php skip installation medium`  
`php yellow.php skip installation large`  

## Settings

The following files will be modified during the installation:

`system/extensions/yellow-system.ini` = file with system settings  
`system/extensions/yellow-language.ini` = file with language settings  
`system/extensions/yellow-user.ini` = file with user settings  
`system/extensions/yellow-extension.ini` = file with extension settings  
`system/extensions/yellow-website.log` = log file of the website  

The following files will be customised during the installation:

`content/1-home/page.md` = content file for home page  
`content/9-about/page.md` = content file for information page  
`content/shared/page-new-default.md` = content file for new page  
`content/shared/page-new-wiki.md` = content file for new wiki page, [if wiki was selected](https://github.com/annaesvensson/yellow-wiki)  
`content/shared/page-new-blog.md` = content file for new blog page, [if blog was selected](https://github.com/annaesvensson/yellow-blog)  
`content/shared/page-error-404.md` = content file for error page  

## Acknowledgements

This extension includes [translations](https://github.com/annaesvensson/yellow-language) by various contributors. Thank you for the good work.

## Developer

Anna Svensson. [Get help](https://datenstrom.se/yellow/help/).
