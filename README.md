MarkupHTMLMinifier
==================

Minify html, inline css and js using code.google.com/p/minify/

## Install

- Install composer and add "mrclay/minify": "2.*" package

- include vendor/autoload.php at the end of your site/config.php

- optional but recommended: protect your vendor directory from web access, add
    ```
    RewriteCond %{REQUEST_URI} (^|/)vendor/.*$ [OR]
    ```
    before the other condition in your pw .htaccess file

- Install this module using PW admin interface