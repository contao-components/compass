Compass
=======

This is a customized package of the [Compass][1] CSS authoring framework to be
integrated in [Contao Open Source CMS][2].


Differences
-----------

We are using a native SASS `compact()` function, since the [PHP compiler][3]
does not provide it. Also, since the compiler only implements SASS 3.2.12, we
cannot use a Compass version greater than 0.12.2.


[1]: http://compass-style.org
[2]: https://contao.org
[3]: https://github.com/leafo/scssphp/
