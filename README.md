Pimple 2.x for Hack [![Build Status](https://travis-ci.org/mcuadros/pimple-hack.png?branch=master)](https://travis-ci.org/mcuadros/cli-array-editor)
==============================

A [Pimple](https://github.com/fabpot/Pimple) version in Hack/HHVM, just for fun! 

Requirements
------------

* HHVM >= 2.5.0;
* Unix system;


Installation
------------

The recommended way to install pimple-hack is [through composer](http://getcomposer.org).
You can see [package information on Packagist.](https://packagist.org/packages/mcuadros/pimple-hack)

```JSON
{
    "require": {
        "mcuadros/pimple-hack": "dev"
    }
}
```


Benchmarking
---------

Just as a learning practice, i made this port of pimple for hack, [this](https://gist.github.com/mcuadros/10937820) are the results of my little benchmarks based on 1 million of iterations, where the hack version is a 30% faster than the original PHP version.


Tests
-----

Tests are in the `tests` folder.
To run them, you need PHPUnit.
Example:

    $ phpunit --configuration phpunit.xml.dist


License
-------

MIT, see [LICENSE](LICENSE)
