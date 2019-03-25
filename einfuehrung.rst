Einführung
==========

Am 3.12.2018 trat die Verordnung (EU) 2018/302 des europäischen Parlaments und des Rates gegen ungerechtfertigtes Geo-Blocking im Binnenmarkt (GB-Verordnung) in Kraft. In Folge dieser Verordnung muss sichergestellt werden, dass Kunden aus allen EU-Mitgliedsstaaten Zugang zu jedem Onlineshop haben, der Waren innerhalb der Europäischen Union anbietet. Dabei sind zwei Aspekte hervorzuheben. Zum einen dürfen Kunden nicht von der Nutzung von Webseiten ausgeschlossen werden, zum anderen sind unterschiedliche Vertragskonditionen - also Preise und Zahlungsgebühren - auf Grundlage der Staatsangehörigleit, des Wohnsitzes oder der Niederlassung unzulässig. Die Geoblocking-Verordnung gilt für den B2C- und den B2B-Handel. Weiterführende Information finden Sie im `Gastblog: E-Commerce international – 8 Fragen zur Geoblocking-VO <https://blog.oxid-esales.com/2018/08/8-fragen-zur-geoblocking-vo/>`_ auf unserer Firmen-Webseite.

Das Modul Geoblocking stellt Funktionen bereit, welche eine komfortable Umsetzung der Geoblocking-Verordnung im OXID eShop ermöglichen. Diese gehen über die Lösung hinaus, die mit shopeigenen Einstellungen erreicht werden kann und im Blockbeitrag `Geoblocking-Verordnung: Wie konfiguriere ich OXID eShop um konform zu sein? <https://oxidforge.org/de/faq-geoblocking.html>`_ auf der OXIDforge vorgestellt wurde.

Shopbetreuer müssen sicherstellen, dass jeder Kunde aus einem europäischen Mitgliedsstaat im Onlineshop Waren bestellen darf. Das automatische Umleiten von Kunde auf länderspezifische Shops aufgrund ihrer IP-Adresse ist ohne ausdrückliche Zustimmung verboten. Der Shopbetreiber ist aber nicht dazu verpflichtet, die bestellte Ware in das Land des Kunden zu versenden, wenn dieses nicht im Liefergebiet liegt. Es ist ausreichend, die Abholung durch den Kunden innerhalb des Liefergebietes zu ermöglichen.

Das Modul Geoblocking bringt eine Einstellung mit, um Länder von der Lieferung auszuschließen. Es prüft darüber hinaus im Bestellprozess das Land, aus dem der Kunde bestellt. Gehört dieses nicht zum Liefergebiet, wird der Kunde zur Eingabe einer Lieferadresse innerhalb des Liefergebietes aufgefordert. Ohne gültige Lieferadresse kann die Bestellung nicht abgeschlossen werden. Der Shopbetreiber kann auch pro Land eine Abholadresse festlegen, welche dem Kunden bei der Bestellung zur Auswahl angeboten wird.

.. |logo| image:: /media/icons/noriskgroup.png
               :class: no-shadow

|logo| Die Businesslogik des Moduls basiert auf einer Contribution der `norisk Group <https://norisk.group/>`_. Von unserem Partner erhielten wir ein Modul für ältere Versionen des OXID eShop und adaptierten es für dieses Geoblocking-Modul. Falls Sie eine ältere Shopversion (< Version 6) betreiben, können sie wegen des Moduls gern direkt bei der norisk Group anfragen.

Die Funktionen im Überblick
---------------------------

* Umsetzung der Geoblocking-Verordnung (EU 2018/302) hinsichtlich der europaweiten Nutzung des Angebotes von Onlineshops
* Länder können festgelegt werden, in welche nicht geliefert wird
* für Länder im Liefergebiet können Abholadressen eingerichtet werden
* Kunden, die aus europäischen Ländern bestellen, in die keine Lieferung erfolgt, werden zur Angabe einer gültigen Lieferadresse aufgefordert
* Bestellung von Kunden werden nur dann ermöglicht, wenn eine gültige Lieferadresse benannt oder eine Abholadresse ausgewählt wurde

.. seealso:: `Verordnung (EU) 2018/302 des europäischen Parlaments und des Rates gegen ungerechtfertigtes Geo-Blocking im Binnenmarkt (GB-Verordnung) <https://eur-lex.europa.eu/legal-content/DE/TXT/HTML/?uri=CELEX:32018R0302&from=DE>`_

.. Intern: oxdaar, Status: