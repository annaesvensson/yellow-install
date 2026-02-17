# Install 0.9.9

Install a brand new website. Developed by Anna Svensson.

<p align="center"><img src="screenshot.png" alt="Screenshot" /></p>

## How to install a website

[Follow the installation instructions](https://datenstrom.se/yellow/help/how-to-get-started). You are greeted with a hello, can create a [user account](https://github.com/annaesvensson/yellow-edit) and select a [language](https://github.com/annaesvensson/yellow-language). You can also choose what kind of website you want to make. The `Small website` option installs only the most important things for small websites. The `Small wiki` option also installs the [wiki extension](https://github.com/annaesvensson/yellow-wiki). The `Small blog` option also installs the [blog extension](https://github.com/annaesvensson/yellow-blog). You can install more extensions later. If there are problems during installation an error message and a link to the [troubleshooting](https://datenstrom.se/yellow/help/troubleshooting) will be displayed.

## How to skip the installation

You can skip the installation at the [command line](https://github.com/annaesvensson/yellow-core). This is convenient for developers who want to run automatic installations and system tests. Open a terminal window. Go to your installation folder, where the file `yellow.php` is. Type `php yellow.php skip installation` followed by an option. The `small` option installs only the most important things for small websites. The `medium` option installs the [help extension](https://github.com/annaesvensson/yellow-help) together with recommended extensions. The `large` option installs all [extensions on the official website](https://datenstrom.se/yellow/extensions/).

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
