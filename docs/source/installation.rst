.. _installation:

Installation
============

Prerequisites
-------------

- Python 3.9 or newer

We recommend installing urlwatch in an isolated environment (virtualenv or
pipx) to avoid interfering with other Python packages.

Install with pip
----------------

Use pip inside an existing virtual environment (or add ``--user`` if you
prefer a user-local install):

.. code-block:: bash

    python -m pip install urlwatch

Install with pipx
-----------------

If you want urlwatch available as a standalone CLI without managing a
virtual environment yourself:

.. code-block:: bash

    pipx install urlwatch

Upgrade an existing installation
--------------------------------

To update to the latest release from PyPI:

.. code-block:: bash

    python -m pip install --upgrade urlwatch

Install from source
-------------------

Clone the repository and install from the checkout directory:

.. code-block:: bash

    git clone https://github.com/thp/urlwatch.git
    cd urlwatch
    python -m pip install .

Verify the installation
-----------------------

Check that urlwatch is on your ``PATH`` and prints a version number:

.. code-block:: bash

    urlwatch --version

Next steps
----------

Continue with :doc:`introduction` for the Quick Start and initial
configuration. For optional dependencies that enable additional filters and
reporters, see :doc:`dependencies`.
