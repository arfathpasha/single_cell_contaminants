.. highlight:: shell

============
Installation
============


.. Stable release
.. --------------

.. To install single_cell_contaminants, run this command in your terminal:

.. .. code-block:: console

..     $ pip install single_cell_contaminants

.. This is the preferred method to install single_cell_contaminants, as it will always install the most recent stable release.

.. If you don't have `pip`_ installed, this `Python installation guide`_ can guide you through the process.

.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/


From sources
------------

The sources for single_cell_contaminants can be downloaded from the `Github repo`_.

You can either clone the public repository:

.. code-block:: console

    $ git clone git://github.com/arfathpasha/single_cell_contaminants

Or download the `tarball`_:

.. code-block:: console

    $ curl -OJL https://github.com/arfathpasha/single_cell_contaminants/tarball/master

Once you have a copy of the source, you can set up it with:

.. code-block:: console

      $ virtualenv venv
      $ source venv/bin/activate
      $ pip install -r requirements_dev.txt
      $ make test
..    $ python setup.py install
      


.. _Github repo: https://github.com/arfathpasha/single_cell_contaminants
.. _tarball: https://github.com/arfathpasha/single_cell_contaminants/tarball/master
