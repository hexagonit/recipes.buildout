============================================
Development buildout for zc.buildout recipes
============================================

This is a development buildout for the hexagonit.recipe.* recipes for
`zc.buildout <http://pypi.python.org/pypi/zc.buildout>`_. It currently
contains the following recipes

    * `hexagonit.recipe.download <http://pypi.python.org/pypi/hexagonit.recipe.download>`_
    * `hexagonit.recipe.cmmi <http://pypi.python.org/pypi/hexagonit.recipe.cmmi>`_

Bootstrapping
-------------

To bootstrap the buildout use the following command::

    $ python bootstrap.py --distribute

Currently supported Python versions for the recipes include version 2.4 - 2.7.

Building
--------

The buildout uses the `mr.developer <http://pypi.python.org/pypi/mr.developer`
extension to clone the recipe repositories automatically. Simply running::

    $ ./bin/buildout

should set everything up for development.

Testing
-------

Tests are run by the following command::

    $ ./bin/test
