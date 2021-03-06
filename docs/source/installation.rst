Installation
============

There are multiple ways of installing conu.

From COPR
---------

At the moment we only support Fedora:

.. code-block:: bash

    dnf copr enable ttomecek/conu
    dnf install python{2,3}-conu conu-doc



From PyPI
---------

.. code-block:: bash

    pip install --user conu


From git
--------

Clone the upstream git repository:

.. code-block:: bash

   git clone https://github.com/fedora-modularity/conu

If using Fedora, use the provided helper script to install dependencies:

.. code-block:: bash

   sh conu/requirements.sh

When not using Fedora, you should figure out the dependencies on your own.

And finally, install conu into python sitelib:

.. code-block:: bash

   pip3 install --user ./conu
