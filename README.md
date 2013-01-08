Drupal installer
================

This is a simple Composer package that will install Drupal at the root of your Composer project.

Drupal is not directly contained in this project. It is downloaded from the drupal.org website.


Installing Drupal using this Composer package:
----------------------------------------------

Not used to Composer? The first step is installing Composer. 
This is essentially a one line process:

```bash
curl -s https://getcomposer.org/installer | php
```

Windows users can download the phar file here: [http://getcomposer.org/download/](install composer).
Then create a *composer.json* file at the root of your project:

```json
{
    "require": {
        "thecodingmachine/drupal": "~7.18"
    }
}
```

and finally, run

```bash
php composer.phar install
```

This will download and unpack the Drupal archive at the root of your project.
In this example, the version downloaded is 7.18 or greater, but lower than 8.0 (this is the meaning of the ~ just before the version number).

Find more:
----------

Want to learn more about this package? Check out <a href="http://blog.thecodingmachine.com/content/installing-drupal-using-composer">the original blog post presenting *thecodingmachine/composer*</a>
