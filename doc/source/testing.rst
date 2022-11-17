.. _testing:

*******
Testing
*******

This chapter documents the internal self-tests of the library.  The
tests are all implemented as Python :mod:`unittest`\s, and can be run
using the standard :mod:`unittest` framework.  The easiest way to
build and test the library is through the ``pytest`` command::

   pytest

.. toctree::
   :glob:

   tests/*

.. automodule:: exactpack.tests
   :members:

