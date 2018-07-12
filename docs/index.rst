.. pyreaper documentation master file, created by
   sphinx-quickstart on Fri Sep  4 18:38:55 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

pyreaper
========

.. automodule:: pyreaper


Installation guide
------------------

Before installing, first make sure you have the Python packages ``numpy`` and
``cython`` installed.  For example, you can install these packages via the
command:

.. code::

   pip install numpy cython

Then run:

.. code::

   pip install git+https://github.com/voicesauce/pyreaper

or instead of using pip, do:

.. code::

   git clone https://github.com/voicesauce/pyreaper
   cd pyreaper
   git submodule update --init --recursive
   python setup.py develop # OR pip setup.py install

This should resolve the package dependencies and install ``pyreaper`` property.


API
---

.. autosummary::
   :toctree: generated/

   pyreaper.reaper


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
