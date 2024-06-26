PyUblas provides a seamless glue layer between
`Numpy <http://www.numpy.org>`_ and
`Boost.Ublas <http://www.boost.org/doc/libs/1_35_0/libs/numeric/ublas/doc/index.htm>`_
for use with
`Boost.Python <http://www.boost.org/doc/libs/1_35_0/libs/python/doc/index.html>`_.

What does that mean? When writing
`hybrid scientific code <https://mathema.tician.de/on-hybrid-scientific-codes-part-i-the-idea/>`_,
one of the main problems is that abstractions that
exist in the high-level language go away or become unwieldy in the
low-level language. Sometimes libraries exist in both languages for
these abstractions, but they refuse to talk to each other. PyUblas is
a bridge between two such libraries, for some of the main
abstractions used in scientific codes, namely vectors and matrices.

Documentation
=============

See the
`PyUblas Documentation <https://documen.tician.de/pyublas/>`_
page.

PyUblasExt
==========

PyUblasExt is a companion to PyUblas and exposes a variety of useful
additions to PyUblas, such as an "operator" class, matrix-free linear
system solvers and eigensolvers. Interested? Head over to the
`PyUblasExt <https://mathema.tician.de/pyublasext/>`_
page.

