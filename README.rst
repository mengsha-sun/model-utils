========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - |
        |
    * - package
      - | |commits-since|

.. |commits-since| image:: https://img.shields.io/github/commits-since/mengsha-sun/model-utils/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/mengsha-sun/model-utils/compare/v0.0.0...master



.. end-badges

Utils for modeling.

Installation
============

::

    pip install model-utils

You can also install the in-development version with::

    pip install https://github.com/mengsha-sun/model-utils/archive/master.zip


Documentation
=============


To use the project:

.. code-block:: python

    import model_utils
    model_utils.longest()


Development
===========

To run all the tests run::

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
