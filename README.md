php-plots
=========

PHP based web index for image displaying.

Original code from Giovanni Petrucciani (@gpetruc) and @musella.

This project contains a PHP web index script to help visualizing folders with many images + other text content.

It is tailored to people working in High Energy Physics that use ROOT (http://root.cern.ch) to produce their plots.

# Setup

1. cd into your web folder
```
cd <my-path> (e.g. /www/project)
```
        
1. Clone this repository

```
git clone https://github.com/artlbv/php-plots.git .
```
        
1. Copy the example/htaccess file into .htaccess and edit its content to suit your needs.
```
cp -p example/htaccess .htaccess
$EDITOR .htacces
```
Note that the webersver should have permissions to access the files/folders (`chmod 755`)

1. Open the web folder into your browser.

1. Enjoy.


# Features

1. Detect if a file is present with multiple formats.

1. Filter files to be selected with wild-cards or regex.

1. Zoom in/out images with double-click.

1. Rearrange images with drag and drop.

1. Overlay content of .txt version on mouse hover.

# Example

https://alobanov.web.cern.ch/public/php-plots/example/
