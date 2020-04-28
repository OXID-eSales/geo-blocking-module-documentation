Installation
============

Dieses Dokument beschreibt die Installation des Moduls Geoblocking für den OXID eShop Version 6.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

Systemvoraussetzungen
---------------------
Für das Modul Geoblocking sind keine speziellen Systemvoraussetzungen notwendig. Es gelten die des OXID eShop ab Version 6.0: https://docs.oxid-esales.com/eshop/de/6.0/installation/neu-installation/server-und-systemvoraussetzungen.html.

--------------------------------------------------

Neu-Installation
----------------

|schritt| Modul installieren
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul wird aus dem Repository heruntergeladen und installiert. Dazu wird per Konsole folgendes Composer-Kommando im Hauptverzeichnis des Shops ausgeführt:

.. code:: bash

   composer require --update-no-dev oxid-esales/geo-blocking-module


|schritt| Modul aktivieren
^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul muss im Shop unter :menuselection:`Erweiterungen --> Module` aktiviert werden. Auf der Registerkarte :guilabel:`Stamm` des Moduls betätigen Sie die Schaltfläche :guilabel:`Aktivieren`.

|schritt| Temporäre Dateien löschen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Löschen Sie alle Dateien und Ordner außer der :file:`.htaccess` aus dem Verzeichnis :file:`/tmp` des Shops.


.. Intern: oxdaas, Status: