# Shopify-Apps (Public Or private)
====================================================================
Giithub shopify PUBLIC Api file
========================================================================
1- Install Composer In Your Project (linux)

(i)Run this in your command line:
   curl -sS https://getcomposer.org/installer | php
   Or download composer.phar into your project root.
(ii)Install Dependencies
    Execute this in your project root.

(iii)php composer.phar install
    Autoload Dependencies
    If your packages specify autoloading information, you can autoload all the dependencies by adding this to your code:
    require 'vendor/autoload.php';
    for mor info please visit:- https://packagist.org/
2- Create your app. Use http://path-to-new_prj/oauth.php as the Callback URL

3- Get the app's credentials and update conf.php
4- Intall the app on a store by visiting http://path-to-new_prj/install.php?shop=example-shop.myshopify.com
5- An OAuth token for the shop should now be stored in the session. Check out the other .php files and see how they work.  
========================================================================
Giithub shopify Private Api file
===========================================================================
1- Install Composer In Your Project
(i)Run this in your command line:
   curl -sS https://getcomposer.org/installer | php
   Or download composer.phar into your project root.
(ii)Install Dependencies
    Execute this in your project root.

(iii)php composer.phar install
    Autoload Dependencies
    If your packages specify autoloading information, you can autoload all the dependencies by adding this to your code:
    require 'vendor/autoload.php';
    for mor info please visit:- https://packagist.org/
2-Create a private app.
3-Update conf.php with the private app's credentials.
4-Check out the .php files and see how they work. (e.g., http://path-to-new_prj/get_shop.php)

I HAVE ALREADY INSTALL COMPOSER FOLDER SO NO NEED TO INSTALL COMPOSER ON IT.
