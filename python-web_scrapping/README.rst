========
Overview
========

Web scrapper project from Automate The Boring Stuff

* Free software: BSD 2-Clause License

Installation
============

::

    pip install web-scrapping

You can also install the in-development version with::

    pip install git+ssh://git@python-web-scrapping/web-scrapping/python-web_scrapping.git@master

Documentation
=============


https://python-web_scrapping.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
