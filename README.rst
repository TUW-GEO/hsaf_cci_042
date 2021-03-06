This package was integrated into the `esa_cci_sm package`_, therefore this package is obsolete and archived.

.. _esa_cci_sm package: https://github.com/TUW-GEO/esa_cci_sm

============
hsaf_cci_042
============


.. image:: https://travis-ci.org/TUW-GEO/hsaf_cci_042.svg?branch=master
    :target: https://travis-ci.org/TUW-GEO/hsaf_cci_042

.. image:: https://coveralls.io/repos/github/TUW-GEO/hsaf_cci_042/badge.svg?branch=master
    :target: https://coveralls.io/github/TUW-GEO/hsaf_cci_042?branch=master

.. image:: https://readthedocs.org/projects/hsaf-cci-042/badge/?version=latest
    :target: http://hsaf-cci-042.readthedocs.io/en/latest/?badge=latest

Reading and reshuffling of CCI soil moisture Written in Python.

Installation
============

Setup of a complete environment with `conda
<http://conda.pydata.org/miniconda.html>`_ can be performed using the following
commands:

.. code-block:: shell

  git clone git@github.com:TUW-GEO/hsaf_cci_042.git hsaf_cci_042
  cd hsaf_cci_042
  conda env create -f environment.yml
  source activate hsaf_env

Supported Products
==================

At the moment this package supports ESA CCI soil moisture data version
v04.2 and v04.3 in netCDF format (reading and time series creation)
with a spatial sampling of 0.25 degrees.

Contribute
==========

We are happy if you want to contribute. Please raise an issue explaining what
is missing or if you find a bug. We will also gladly accept pull requests
against our master branch for new features or bug fixes.

Development setup
-----------------

For Development we also recommend a ``conda`` environment. You can create one
including test dependencies and debugger by running
``conda env create -f environment.yml``. This will create a new ``hsaf_env``
environment which you can activate by using ``source activate hsaf_env``.

Guidelines
----------

If you want to contribute please follow these steps:

- Fork the hsaf_cci_042 repository to your account
- Clone the repository, make sure you use ``git clone --recursive`` to also get
  the test data repository.
- make a new feature branch from the hsaf_cci_042 master branch
- Add your feature
- Please include tests for your contributions in one of the test directories.
  We use py.test so a simple function called test_my_feature is enough
- submit a pull request to our master branch

Note
====

This project has been set up using PyScaffold 2.5. For details and usage
information on PyScaffold see http://pyscaffold.readthedocs.org/.
