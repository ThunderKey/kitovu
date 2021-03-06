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

.. |docs| image:: https://readthedocs.org/projects/kitovu/badge/?style=flat
    :target: https://readthedocs.org/projects/kitovu
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/kitovu-bot/kitovu.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/kitovu-bot/kitovu

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/kitovu-bot/kitovu?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/kitovu-bot/kitovu

.. |requires| image:: https://requires.io/github/kitovu-bot/kitovu/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/kitovu-bot/kitovu/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/kitovu-bot/kitovu/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/kitovu-bot/kitovu

.. |version| image:: https://img.shields.io/pypi/v/kitovu.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/kitovu

.. |commits-since| image:: https://img.shields.io/github/commits-since/kitovu-bot/kitovu/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/kitovu-bot/kitovu/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/kitovu.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/kitovu

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/kitovu.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/kitovu

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/kitovu.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/kitovu


.. end-badges

OpenHSR Connect 2

* Free software: BSD 2-Clause License

Installation
============

::

    pip install kitovu

Documentation
=============

https://kitovu.readthedocs.io/

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
