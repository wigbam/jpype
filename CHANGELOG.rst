Changelog
=========

This changelog *only* contains changes from the *first* pypi release (0.5.4.3) onwards.

0.5.4.6 (2013-09-06 15:05)
~~~~~~~~~~~~~~~~~~~~~~~~~~

Added AHL changes:

* replaced Python set type usage with new 2.6.x and higher
* fixed broken Python slicing semantics on JArray objects
* fixed a memory leak in the JVM when passing Python lists to JArray constructors
* prevent ctrl+c seg faulting
* corrected new[]/delete pairs to stop valgrind complaining
* ship basic PyMemoryView implementation (based on numpy's) for Python 2.6 compatibility

0.5.4.5 (2013-08-25 12:12)
~~~~~~~~~~~~~~~~~~~~~~~~~~

* Added support for OSX 10.9 Mavericks by @rmangino (#16)

0.5.4.4 (2013-08-10 19:30)
~~~~~~~~~~~~~~~~~~~~~~~~~~

* Rewritten Java Home directory Search by @marsam (#13, #12 and #7)
* Stylistic cleanups of setup.py

0.5.4.3 (2013-07-27 14:00)
~~~~~~~~~~~~~~~~~~~~~~~~~~

Initial pypi release with most fixes for easier installation
