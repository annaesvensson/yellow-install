<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Install 0.8.90

Install a brand new website.

<p align="center"><img src="install-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install a website

[Follow the installation instructions](https://datenstrom.se/yellow/help/how-to-get-started). First the installer checks whether all installation requirements have been met. Then the installer helps you with setting up your website. After the installer has done its work it will delete itself. Your website is immediately available. The most important things for small websites are included. You can add features, languages and themes.

## How to uninstall a website

Delete all files in the installation folder.

## Settings

The following settings will be configured during installation:

`system/extensions/yellow-system.ini` = file with system settings  
`system/extensions/yellow-language.ini` = file with language settings  
`system/extensions/yellow-user.ini` = file with user settings  

The following files will be customised during installation:

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
