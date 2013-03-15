phpBB Russian Language Pack installer
=========================

This package is an installer that will download phpBB Russian Language Pack from the http://phpbb.com website and unpack it at Composer project.

phpBB is not directly contained in this project. It is downloaded from the phpbb.com website.


Installing phpBB Russian language pack using this Composer package:
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
        "sergeym/phpbb-translation-russian": "~1.0"
    }
}
```

and finally, run

```bash
php composer.phar install
```

This will download and unpack the phpBB Russian Language Pack archive at the root of your project.
In this example, the version downloaded is 1.0 or greater, but lower than 2.0 (this is the meaning of the ~ just before the version number).
