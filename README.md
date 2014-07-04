MarkupHTMLMinifier
==================

Minify html, inline css and js using code.google.com/p/minify/

## Install

- Install composer and add "mrclay/minify": "2.*" package

- include vendor/autoload.php at the end of your site/config.php

- optional but recommended: protect your vendor directory from web access, add
    ```
    RewriteCond %{REQUEST_URI} ^/vendor/.*$ [OR]
    ```
    before the other conditions in your pw .htaccess file

- Install this module using PW admin interface

- Now you should see generated html source minified. Note: this also remove the
  horizontal 4px margin in your inline lists, so update your styles if needed.