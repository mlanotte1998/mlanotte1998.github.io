
mlanotte1998.github.io
===============================

Common code usable by all Tendrl sds side components

* Free software: LGPL2.1
* Documentation: https://github.com/Tendrl/commons/tree/master/doc/source
* Source: https://github.com/Tendrl/commons
* Bugs: https://github.com/Tendrl/commons/issues

Folders
--------

* old_code = Code from the early stages when I was experimenting with different templates 
* other_files = Includes files other than photos and templates, such as pdfs
* photos = Includes all images used on the website


Release process
---------------

When you are ready to cut a new version:

#. Bump the version number in ``tendrl/commons/__init__.py`` and commit your
   changes.
   ::

      python setup.py bumpversion

#. Tag and push to GitHub.
   ::

      python setup.py release

#. Make an SRPM.
   ::

      make srpm



Developer/Install documentation
-------------------------------

We also have sphinx documentation in ``docs/source``.

*To build it, run:*

::

    $ python setup.py build_sphinx
