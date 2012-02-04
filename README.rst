Bz2file is a Python library for reading and writing bzip2-compressed files.

It contains a drop-in replacement for the standard library's ``bz2.BZ2File``
class, including features from the latest development version of CPython that
are not available in older releases.

Bz2file is compatible with Python 2.6, 2.7, and 3.0 through 3.3.


Features
--------

- Supports multi-stream files.

- Can read from/write to any file-like object.

- Added methods: ``peek()``, ``read1()``, ``readinto()``, ``fileno()``,
  ``readable()``, ``writable()``, ``seekable()``.


Installation
------------

To install bz2file, run: ::

   $ pip install bz2file


Documentation
-------------

The ``BZ2File`` class in this module provides the same features and interface as
the ``bz2.BZ2File`` class in the current development version of CPython,
`documented here <http://docs.python.org/dev/library/bz2.html#bz2.BZ2File>`_.
