Installation
============

Installieren Sie das Modul Geoblocking für den OXID eShop Version 7.

Systemvoraussetzungen
---------------------
Für das Modul Geoblocking sind keine speziellen Systemvoraussetzungen notwendig.

Es gelten die des OXID eShop ab Version 7.2: https://docs.oxid-esales.com/eshop/de/7.2/installation/neu-installation/server-und-systemvoraussetzungen.html.


Neuinstallation
---------------

1. Laden Sie das Modul aus dem Repository herunter und installieren Sie es.

   Führen Sie dazu im Hauptverzeichnis des Shops den folgenden Composer-Befehl über die Konsole aus:

   .. code:: bash

      composer require --update-no-dev oxid-esales/geo-blocking-module:^2.2.0

#. Um das Modul zu aktivieren, führen Sie einen der folgenden Schritte aus:

   * Um das Modul automatisch über die OXID eShop-Konsole zu aktivieren, gehen Sie wie folgt vor:

     a. Falls zutreffend, passen Sie die Subshop-ID im folgenden Befehl an:

        .. code:: bash

           ./vendor/bin/oe-console oe:module:activate --shop-id=<subshop-id> oegeoblocking

     b. Führen Sie den Befehl aus, in unserem Beispiel für den Subshop :productname:`OXID eShop Enterprise B2B Edition` mit der Shop-ID 3:

        .. code:: bash

           ./vendor/bin/oe-console oe:module:activate --shop-id=3 oegeoblocking

   * Um das Modul manuell zu aktivieren, wählen Sie im Shop unter :menuselection:`Erweiterungen --> Module` auf der Registerkarte :guilabel:`Stamm` die Schaltfläche :guilabel:`Aktivieren`.


.. Intern: oxdaas, Status: