# Install 0.9.7

Install a brand new website. Developed by Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Screenshot"></p>

## How to install a website

[Follow the installation instructions](https://datenstrom.se/yellow/help/how-to-get-started). You are greeted with a hello, can create a [user account](https://github.com/annaesvensson/yellow-edit) and select your [language](https://github.com/annaesvensson/yellow-language). The installer helps you with setting up your website and makes sure all installation requirements have been met. If there are problems during installation the installer will display an error message and a link to the [troubleshooting](https://datenstrom.se/yellow/help/troubleshooting).

## How to skip the installation

You can skip the installation at the [command line](https://github.com/annaesvensson/yellow-core). Open a terminal window. Go to your installation folder, where the file `yellow.php` is. Type `php yellow.php skip installation` followed by an option. The `small` option installs only the most important things for small websites, this is the same as the standard installation with the English language. The `medium` option installs the [help extension](https://github.com/annaesvensson/yellow-help) together with recommended extensions, this is useful if you want to do performance testing. The `large` option installs all available extensions, this is useful if you want to run system tests.

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
`system/extensions/yellow-website.log` = log file of the website  

The following files will be customised during the installation:

`content/1-home/page.md` = content file for home page  
`content/9-about/page.md` = content file for information page  
`content/shared/page-new-default.md` = content file for new page  
`content/shared/page-new-wiki.md` = content file for new wiki page, [if wiki was selected](https://github.com/annaesvensson/yellow-wiki)  
`content/shared/page-new-blog.md` = content file for new blog page, [if blog was selected](https://github.com/annaesvensson/yellow-blog)  
`content/shared/page-error-404.md` = content file for error page  

Do you have questions? [Get help](https://datenstrom.se/yellow/help/).
