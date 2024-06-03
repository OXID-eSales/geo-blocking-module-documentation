Installation
============

This document describes the installation of the geo-blocking module for OXID eShop Version 7.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

System requirements
-------------------
No special system requirements are necessary for the geo-blocking module.

The requirements of OXID eShop Version 7.1 or higher apply: https://docs.oxid-esales.com/eshop/en/7.1/installation/new-installation/server-and-system-requirements.html.

--------------------------------------------------

New installation
----------------

|schritt| Installing the module
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Download the module from the repository and install it. To do this, execute the following Composer command in the shop’s main directory via console:

.. code:: bash

   composer require --update-no-dev oxid-esales/geo-blocking-module:^2.1.0


|schritt| Activating the module
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To activate the module, do one of the following:

* To activate the module via the OXID eShop console automatically, do the following:

  .. todo: #HR: Lautet der Befehl wie folgt?; "geo-blocking" with hyphen?

   a. Adjust the subshop ID in the following command:

      .. code:: bash

         ./vendor/bin/oe-console oe:module:activate --shop-id=<subshop-id> geo-blocking

   b. Execute the command, in our example for the :productname:`OXID eShop Enterprise B2B Edition` subshop with store ID 3:

      .. code:: bash

         ./vendor/bin/oe-console oe:module:activate --shop-id=3 geo-blocking

* To activate the module manually, in the shop, under :menuselection:`Extensions --> Modules`, on the :guilabel:`Main` tab, choose :guilabel:`Activate`.

.. todo: #HR |schritt| Deleting temporary files deleted


.. Internal: oxdaas, status: