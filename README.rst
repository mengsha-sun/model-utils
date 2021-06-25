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

    pip install -e git+https://github.com/mengsha-sun/model-utils.git#egg=model_utils

You can also install a specific version or branch with::

    pip install git+https://github.com/mengsha-sun/model-utils.git@v1.0.0#egg=model_utils
    pip install git+https://github.com/mengsha-sun/model-utils.git@master#egg=model_utils



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
