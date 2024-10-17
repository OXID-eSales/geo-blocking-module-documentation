Installation
============

Install the geo-blocking module for OXID e Shop Version 7.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

System requirements
-------------------
No special system requirements are necessary for the geo-blocking module.

The requirements of OXID eShop Version 7.2 or higher apply: https://docs.oxid-esales.com/eshop/en/7.2/installation/new-installation/server-and-system-requirements.html.

New installation
----------------

1. Download the module from the repository and install it.

   To do so, in the shop’s main directory, execute the following Composer command via console:

   .. code:: bash

      composer require --update-no-dev oxid-esales/geo-blocking-module:^2.2.0

#. To activate the module, do one of the following:

   * To activate the module via the OXID eShop console automatically, do the following:

     a. If applicable, adjust the subshop ID in the following command:

        .. code:: bash

           ./vendor/bin/oe-console oe:module:activate --shop-id=<subshop-id> oegeoblocking

     b. Execute the command, in our example for the :productname:`OXID eShop Enterprise B2B Edition` subshop with store ID 3:

        .. code:: bash

           ./vendor/bin/oe-console oe:module:activate --shop-id=3 oegeoblocking

   * To activate the module manually, in the shop, under :menuselection:`Extensions --> Modules`, on the :guilabel:`Main` tab, choose :guilabel:`Activate`.

.. Internal: oxdaas, status: