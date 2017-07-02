========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-hover-cli/badge/?style=flat
    :target: https://readthedocs.org/projects/python-hover-cli
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/python-hover-cli.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/python-hover-cli

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/python-hover-cli?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/python-hover-cli

.. |requires| image:: https://requires.io/github/techdragon/python-hover-cli/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/python-hover-cli/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/techdragon/python-hover-cli/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/techdragon/python-hover-cli

.. |codecov| image:: https://codecov.io/github/techdragon/python-hover-cli/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/python-hover-cli

.. |landscape| image:: https://landscape.io/github/techdragon/python-hover-cli/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/python-hover-cli/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/python-hover-cli/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/python-hover-cli
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/hover-cli.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/hover-cli

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/python-hover-cli/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/python-hover-cli/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/hover-cli.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/hover-cli

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/hover-cli.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/hover-cli

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/hover-cli.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/hover-cli

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/python-hover-cli/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/python-hover-cli/


.. end-badges

Command line tool for querying if a domain name is available using Hover.com's JSON API.

* Free software: MIT license

Installation
============

::

    pip install hover-cli

Documentation
=============

https://python-hover-cli.readthedocs.io/

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
