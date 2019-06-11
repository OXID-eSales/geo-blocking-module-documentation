Introduction
============

The Regulation (EU) 2018/302 of the European Parliament and of the Council on addressing unjustified geo-blocking within the internal market (Geo-blocking Regulation) entered into force on 03/12/2018. As a result of this Regulation, it must be ensured that customers from all EU Member States have access to every online shop offering goods within the European Union. There are two aspects to be emphasised. For one thing, customers must not be excluded from access to websites and for another, different contractual conditions - i.e. prices and payment fees - based on nationality, place of residence or place of establishment are not allowed. The Geo-blocking Regulation applies to B2C and B2B trade. Further information can be found in the German `Guest blog: E-commerce international - 8 questions about the Geo-blocking Regulation <https://blog.oxid-esales.com/2018/08/8-fragen-zur-geoblocking-vo/>`_ on our company website.

The geo-blocking module provides functions that make it easy to implement the Geo-blocking Regulation in OXID eShop. It goes beyond what can be achieved with shop-specific settings and was presented in the German blog post `Geo-blocking Regulation: How to configure OXID eShop to be compliant? <https://oxidforge.org/de/faq-geoblocking.html>`_ on OXIDforge.

Shop owners must ensure that every customer from a European Member State is allowed to order goods in the online shop. Automatic redirection of customers to country-specific shops due to their IP address is prohibited without explicit consent. However, shop owners are not required to ship the ordered goods to the customer’s country if it is not within their delivery area. Customers only need to be able to pick up their good within the delivery area.

The geo-blocking module has a setting to exclude specific countries for delivery. In addition, it checks the country the customer is ordering from and if this is not within the delivery area, the customer is prompted to enter a shipping address within the delivery area. The order cannot be completed without a valid shipping address. The shop owner can also specify one pickup address per country, which the customer can select when ordering.

.. |logo| image:: /media/icons/noriskgroup.png
               :class: no-shadow

|logo| The business logic of the module is based on a contribution from `norisk Group <https://norisk.group/>`_. Our partner gave us a module for older versions of OXID eShop which we adapted for our geo-blocking module. If you use an older version of the shop (< Version 6), you are welcome to inquire about the module directly with norisk Group.

Functions at a glance
---------------------

* Implementation of the Geo-blocking Regulation (EU 2018/302) with regard to the Europe-wide use of online shop offerings
* Ability to specify countries to which delivery is not made
* Pickup addresses can be set up for countries within the delivery area
* Customers ordering from European countries to which delivery is not made will be asked to provide a valid shipping address
* Customers can only place orders if a valid shipping address has been specified or a pickup address has been selected

.. seealso:: `Regulation (EU) 2018/302 of the European Parliament and of the Council on addressing unjustified geo-blocking within the internal market (Geo-blocking Regulation) <https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32018R0302&from=EN>`_

.. Internal: oxdaar, status:
