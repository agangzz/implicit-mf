implicitMF
==========

Python implementation of implicit matrix factorization as outlined in http://labs.yahoo.com/files/HuKorenVolinsky-ICDM08.pdf.

Requires numpy version 1.7.1 or greater and scipy version 0.12.0 or greater.

This fork adds a multithreaded version: ```mf_threads.py``` that speeds things up a little bit.

Note: because of Python's GIL, we actually use processes, not threads.
