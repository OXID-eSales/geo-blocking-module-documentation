Installation
============

This document describes the installation of the geo-blocking module for OXID eShop Version 6.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

System requirements
-------------------
No special system requirements are necessary for the geo-blocking module. The requirements of OXID eShop Version 6.0 or higher apply: https://docs.oxid-esales.com/eshop/en/6.1/installation/new-installation/server-and-system-requirements.html.

--------------------------------------------------

New installation
----------------

|schritt| Installing the module
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Download the module from the repository and install it. To do this, execute the following Composer command in the shop’s main directory via console:

.. code:: bash

   composer require --update-no-dev oxid-esales/geo-blocking-module


|schritt| Activating the module
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
The module must be activated in the shop under :menuselection:`Extensions --> Modules`. To do this, click on :guilabel:`Activate` in the module’s :guilabel:`Main` tab.

|schritt| Deleting temporary files
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Delete all files and folders except :file:`.htaccess` from the shop’s :file:`/tmp` directory.


.. Internal: oxdaas, status: