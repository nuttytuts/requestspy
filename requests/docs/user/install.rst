.. _install:

Installation of Requests
========================

.. image:: https://farm5.staticflickr.com/4230/35550376215_da1bf77a8c_k_d.jpg


This part of the documentation covers the installation of Requests.
The first step to using any software package is getting it properly installed.


$ pipenv install requests
-------------------------

To install Requests, simply run this simple command in your terminal of choice::

    $ pipenv install requests

If you don't have `pipenv <http://pipenv.org/>`_ installed (tisk tisk!), head over to the Pipenv website for installation instructions. Or, if you prefer to just use pip and don't have it installed,
`this Python installation guide <https://requests.readthedocs.io/en/master/user/install/>`_
can guide you through the process.

Get the Source Code
-------------------

Requests is actively developed on GitHub, where the code is
`always available <https://github.com/psf/requests>`_.

You can either clone the public repository::

    $ git clone git://github.com/psf/requests.git

Or, download the `tarball <https://github.com/psf/requests/tarball/master>`_::

    $ curl -OL https://github.com/psf/requests/tarball/master
    # optionally, zipball is also available (for Windows users).

Once you have a copy of the source, you can embed it in your own Python
package, or install it into your site-packages easily::

    $ cd requests
    $ pip install .
