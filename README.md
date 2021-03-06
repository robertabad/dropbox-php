[![Build
Status](https://travis-ci.org/Dropbox-PHP/dropbox-php.svg?branch=master)](https://travis-ci.org/Dropbox-PHP/dropbox-php)
[![Join the chat at https://gitter.im/Dropbox-PHP/dropbox-php](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Dropbox-PHP/dropbox-php?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Dropbox-php
===========

This PHP library allows you to easily integrate dropbox with PHP.

The following PHP extension is required:

* json

The library makes use of OAuth. At the moment you can use either of these libraries:

[PHP OAuth extension](http://pecl.php.net/package/oauth)  
[PEAR's HTTP_OAUTH package](http://pear.php.net/package/http_oauth)  

The extension is recommended, but if you can't install php extensions you should go for the pear package.  
Installing
----------

    composer require "dropbox-php/dropbox-php" "1.*"

Or by adding the following to your composer.json:

    "require": {
        "dropbox-php/dropbox-php": “1.*”
    }

NOTE: Pear install is no longer supported

Documentation
-------------
Check out the [documentation](http://www.dropbox-php.com/docs).  

Questions?
----------

[Dropbox-php Mailing list](http://groups.google.com/group/dropbox-php)  
[Official Dropbox forums](https://www.dropboxforum.com/hc/communities/public/questions)
 
