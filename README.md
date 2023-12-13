Teknoo Software - Common library
=================================

Metapackage to install [Teknoo East Common](https://github.com/TeknooSoftware/east-common) with Symfony. 

Support this project
---------------------
This project is free and will remain free. It is fully supported by the activities of the EIRL.
If you like it and help me maintain it and evolve it, don't hesitate to support me on
[Patreon](https://patreon.com/teknoo_software) or [Github](https://github.com/sponsors/TeknooSoftware).

Thanks :) Richard.

Credits
-------
EIRL Richard Déloge - <https://deloge.io> - Lead developer.
SASU Teknoo Software - <https://teknoo.software>

About Teknoo Software
---------------------
**Teknoo Software** is a PHP software editor, founded by Richard Déloge, as part of EIRL Richard Déloge.
Teknoo Software's goals : Provide to our partners and to the community a set of high quality services or software,
sharing knowledge and skills.

License
-------
East Common is licensed under the MIT License - see the licenses folder for details.

Installation & Requirements
---------------------------
To install this library with composer, run these commands :

* Add in your composer.json the entry `https://api.github.com/repos/TeknooSoftware/symfony-recipes/contents/index.json`
  to the list `extra.symfony.endpoint` and set to `true` the entry `extra.symfony.allow-contrib`.
* If the `extra.symfony.endpoint` is not already defined, you must also add `flex://defaults` to avoid errors.
* Run this command `composer require teknoo/east-common-symfony`

To start a project with Symfony :

```
symfony new your_project_name new
composer require teknoo/composer-install
composer require teknoo/east-common-symfony    
```

This library requires :

    * PHP 8.1+
    * A PHP autoloader (Composer is recommended)
    * Teknoo/Immutable.
    * Teknoo/States.
    * Teknoo/Recipe.
    * Teknoo/East-Foundation.
    * Optional: Symfony 6.3+ (for administration)

