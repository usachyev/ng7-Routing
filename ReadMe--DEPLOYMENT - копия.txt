---------------------------------------------------------------------------------------------------------------
d:\  NG6\C-US-NG7\ng7-Routing-CLI-Menu5 ●●●\dist\ng7-Routing-CLI-Menu5\
### или
### c:\XAMPP\htdocs\ng7-Routing-CLI-Menu5\
---------------------------------------------------------------------------------------------------------------

Содержимое Deployment папки [ dist \ ng7-Routing-CLI-Menu5 ] в составе :

parent
    |
    |--  .htaccess
    |--  3rdpartylicenses.txt
    |--  favicon.ico
    |--  index.html
    |--  main.2a592c13ca53531877b9.js
    |--  polyfills.5f914c50564a81aae750.js
    |--  ReadMe.txt
    |--  runtime.ec2944dd8b20ec099bf3.js
    |--  styles.3ff695c00d717f2d2a11.css
    |
parent

может находиться либо в корне сайта  [ c:\XAMPP\htdocs\ ]
### либо в любой другой папке 
### ( к примеру -- [ c:\XAMPP\htdocs\ng7-Routing-CLI-Menu5\ ] )

--------------------------------------------------------------------------------------------


Файл  .htaccess  должен выглядеть следующим образом :

#########################################################
# START of C:\XAMPP\htdocs\.htaccess
#########################################################
#<IfModule mod_rewrite.c>
RewriteEngine On
    RewriteBase /
    # If an existing asset or directory is requested go to it as it is
    RewriteCond %{DOCUMENT_ROOT}%{REQUEST_URI} -f [OR]
    RewriteCond %{DOCUMENT_ROOT}%{REQUEST_URI} -d
    RewriteRule ^ - [L]
    # If the requested resource doesn't exist, use index.html
RewriteRule ^ /index.html
Redirect 301 /dashboard/ /index.html
#</IfModule>
#########################################################
# End of C:\XAMPP\htdocs\.htaccess
#########################################################















