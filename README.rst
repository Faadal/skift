skift
######
|PyPI-Status| |PyPI-Versions| |Build-Status| |Codecov| |LICENCE|

``scikit-learn`` wrappers for Python ``fastText``.

.. code-block:: python

  import skift
  # coming soon...

.. contents::

.. section-numbering::


Installation
============

.. code-block:: bash

  pip install skift


Wrappers
=========

``skift`` includes several wrappers: 

Standard Wrappers
-----------------


pandas-dependent wrappers
-------------------------

These wrappers assume the ``X`` parameters given to ``fit``, ``predict``, and ``predict_proba`` methods is a ``pandas.DataFrame`` object:


Contributing
============

Package author and current maintainer is Shay Palachy (shay.palachy@gmail.com); You are more than welcome to approach him for help. Contributions are very welcomed.

Installing for development
----------------------------

Clone:

.. code-block:: bash

  git clone git@github.com:shaypal5/skift.git


Install in development mode:

.. code-block:: bash

  cd skift
  pip install -e .


Running the tests
-----------------

To run the tests use:

.. code-block:: bash

  pip install pytest pytest-cov coverage
  cd skift
  pytest


Adding documentation
--------------------

The project is documented using the `numpy docstring conventions`_, which were chosen as they are perhaps the most widely-spread conventions that are both supported by common tools such as Sphinx and result in human-readable docstrings. When documenting code you add to this project, follow `these conventions`_.

.. _`numpy docstring conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt
.. _`these conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt


Credits
=======

Created by Shay Palachy (shay.palachy@gmail.com).


.. |PyPI-Status| image:: https://img.shields.io/pypi/v/skift.svg
  :target: https://pypi.python.org/pypi/skift

.. |PyPI-Versions| image:: https://img.shields.io/pypi/pyversions/skift.svg
   :target: https://pypi.python.org/pypi/skift

.. |Build-Status| image:: https://travis-ci.org/shaypal5/skift.svg?branch=master
  :target: https://travis-ci.org/shaypal5/skift

.. |LICENCE| image:: https://img.shields.io/github/license/shaypal5/skift.svg
  :target: https://github.com/shaypal5/skift/blob/master/LICENSE

.. |Codecov| image:: https://codecov.io/github/shaypal5/skift/coverage.svg?branch=master
   :target: https://codecov.io/github/shaypal5/skift?branch=master