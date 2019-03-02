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
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/cookiecutter-jsrobin888/badge/?style=flat
    :target: https://readthedocs.org/projects/cookiecutter-jsrobin888
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/jsrobin888/cookiecutter-jsrobin888.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/jsrobin888/cookiecutter-jsrobin888

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/jsrobin888/cookiecutter-jsrobin888?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/jsrobin888/cookiecutter-jsrobin888

.. |requires| image:: https://requires.io/github/jsrobin888/cookiecutter-jsrobin888/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/jsrobin888/cookiecutter-jsrobin888/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/jsrobin888/cookiecutter-jsrobin888/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jsrobin888/cookiecutter-jsrobin888

.. |version| image:: https://img.shields.io/pypi/v/nameless.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/nameless

.. |commits-since| image:: https://img.shields.io/github/commits-since/jsrobin888/cookiecutter-jsrobin888/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/jsrobin888/cookiecutter-jsrobin888/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/nameless.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/nameless

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/nameless.svg
    :alt: Supported versions
    :target: https://pypi.org/project/nameless

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/nameless.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/nameless


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install nameless

Documentation
=============


https://cookiecutter-jsrobin888.readthedocs.io/


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
