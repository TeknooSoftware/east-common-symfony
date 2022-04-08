Teknoo Software - Common library
=================================

Metapackage to install [Teknoo East Common](https://github.com/TeknooSoftware/east-common) with Symfony. 

Installation & Requirements
---------------------------
To install this library with composer, run these commands :

* Add in your composer.json the entry `https://api.github.com/repos/TeknooSoftware/symfony-recipes/contents/index.json`
  to the list `extra.symfony.endpoint` and set to `true` the entry `extra.symfony.allow-contrib`.
* If the `extra.symfony.endpoint` is not already defined, you must also add `flex://defaults` to avoid errors.
* Run this command `composer require teknoo/east-foundation-symfony`

This library requires :

    * PHP 8.1+
    * A PHP autoloader (Composer is recommended)
    * Teknoo/Immutable.
    * Teknoo/States.
    * Teknoo/Recipe.
    * Teknoo/East-Foundation.
    * Optional: Symfony 6.0+ 

Support this project
---------------------

This project is free and will remain free, but it is developed on my personal time. 
If you like it and help me maintain it and evolve it, don't hesitate to support me on [Patreon](https://patreon.com/teknoo_software).
Thanks :) Richard. 

Credits
-------
Richard Déloge - <richarddeloge@gmail.com> - Lead developer.
Teknoo Software - <https://teknoo.software>

About Teknoo Software
---------------------
**Teknoo Software** is a PHP software editor, founded by Richard Déloge.
Teknoo Software's goals : Provide to our partners and to the community a set of high quality services or software,
 sharing knowledge and skills.

License
-------
East Common is licensed under the MIT License - see the licenses folder for details
