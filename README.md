Jonnitto.MultiColumn
====================

[![Latest Stable Version](https://poser.pugx.org/jonnitto/multicolumn/v/stable)](https://packagist.org/packages/jonnitto/multicolumn)
[![Total Downloads](https://poser.pugx.org/jonnitto/multicolumn/downloads)](https://packagist.org/packages/jonnitto/multicolumn)
[![License](https://poser.pugx.org/jonnitto/multicolumn/license)](https://packagist.org/packages/jonnitto/multicolumn)

MultiColumn System for [Neos](https://neos.io). Please bring your own css

Installation
------------
Most of the time you have to make small adjustments to a package (e.g. configuration in Settings.yaml). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under Packages/Sites/. To install it correctly go to your theme package (e.g.Packages/Sites/Foo.Bar) and run following command:

composer require jonnitto/multicolumn --no-update
The --no-update command prevent the automatic update of the dependencies. After the package was added to your theme composer.json, go back to the root of the Neos installation and run composer update. Et voilà! Your desired package is now installed correctly.

Grid
----

Possible grid classes are:

**xs**  
`3, 4, 6, 8, 12`

**sm / md / lg / xl**  
`2, 3, 4, 6, 8, 9, 10`

Classes get rendered like this: `col-BREAKPOINT-NUMBER`, e. g. `col-sm-8`


License
-------

Licensed under MIT, see [LICENSE](LICENSE)
