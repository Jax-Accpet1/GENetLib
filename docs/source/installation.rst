Installation
============


Install from PyPI
------------------
It is recommended to use ``pip`` for installation. You need to check the upgrade at the beginning:

.. code-block:: bash
   
   pip install --upgrade pip

Then you can instll this package using the code:

.. code-block:: bash

   pip install GENetLib

Install from source
---------------------

If you want to work with the latest development version or wish to contribute to **GENetLib**, this way will be suitable.

Clone the latest source code from GitHub and navigate into the directory of the cloned project:

.. code-block:: bash

   git clone https://github.com/Barry57/GENetLib.git
   cd GENetLib

Run the following command to install the project:

.. code-block:: bash

   pip install .

Alternatively, if you want to install the project in development mode (which will install the project along with all development dependencies), you can use:

.. code-block:: bash

   pip install -e .

If you prefer to use the setup.py script to install, you can run:

.. code-block:: bash

   python setup.py install


Dependencies
---------------

Dependencies and version control for running **GENetLib**:

- python >= 3.8
- matplotlib >= 3.7.1
- numpy >= 1.24.3
- pandas >= 1.5.3
- scipy >= 1.10.1
- setuptools >= 67.8.0
- torch >= 2.3.0
