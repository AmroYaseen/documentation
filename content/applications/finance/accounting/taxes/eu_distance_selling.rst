===================================
EU intra-community distance selling
===================================

EU intra-community distance selling involves the cross-border trade of goods and services from
vendors registered for VAT purposes to individuals (B2C) located in a European Union member state.
The transaction is conducted remotely, typically through online platforms, mail orders, telephone,
or other means of communication.

EU intra-community distance selling is subject to specific VAT rules and regulations. The vendor
must charge VAT per the VAT rate applicable in the buyer's country.

.. note::
   This remains applicable even if the vendor is located outside of the European Union.

Configuration
=============

<<<<<<< HEAD
Go to :menuselection:`Accounting/Invoicing --> Settings --> Taxes` and enable **EU intra-community
Distance Selling**.
||||||| parent of ff7204fb5 (temp)
Go to :menuselection:`Accounting/Invoicing --> Settings --> Taxes`, then enable **EU intra-community
Distance Selling** (or **EU Digital Goods VAT** if you created your database before July 1, 2021),
and *Save*.
=======
The **EU Intra-community Distance Selling** feature helps you comply with this regulation by
creating and configuring new **fiscal positions** and **taxes** based on your company's country. To
enable it, go to :menuselection:`Accounting --> Configuration --> Settings --> Taxes`, tick
:guilabel:`EU Intra-community Distance Selling`, and :guilabel:`Save`.
>>>>>>> ff7204fb5 (temp)

.. image:: eu_distance_selling/enable-feature.png
   :alt: EU intra-community Distance Selling feature in Odoo Accounting settings

<<<<<<< HEAD
.. _eu_distance_selling/taxes:

Fiscal Positions and Taxes
==========================

Once enabled, the feature automatically creates all the necessary taxes and fiscal positions needed
for each EU member state, based on your company's country.

We highly recommend checking that the proposed mapping is suitable for the products and services you
sell before using it.

.. _eu_distance_selling/refresh-mapping:

Refresh tax mapping
-------------------

Whenever you add or modify taxes, you can update automatically your fiscal positions.

To do so, go to :menuselection:`Accounting/Invoicing --> Settings --> Taxes --> EU intra-community
Distance Selling` and click on the *Refresh tax mapping* button.
||||||| parent of ff7204fb5 (temp)
.. important::
   Please :ref:`upgrade the module <general/upgrade>` `l10n_eu_service` if you already installed it
   before **July 1, 2021**, or if you activated the feature **EU Digital Goods VAT** in the
   Accounting settings. Then, make sure to :ref:`refresh the tax mapping
   <eu_distance_selling/refresh-mapping>`.

.. _eu_distance_selling/taxes:

Fiscal Positions and Taxes
==========================

Once enabled, the feature automatically creates all the necessary taxes and fiscal positions needed
for each EU member state, based on your company's country.

We highly recommend checking that the proposed mapping is suitable for the products and services you
sell before using it.

.. _eu_distance_selling/refresh-mapping:

Refresh tax mapping
-------------------

Whenever you add or modify taxes, you can update automatically your fiscal positions.

To do so, go to :menuselection:`Accounting/Invoicing --> Settings --> Taxes --> EU intra-community
Distance Selling` and click on the *Refresh tax mapping* button.
=======
.. tip::
   Whenever you add or modify taxes, you can automatically update your fiscal positions. To do so,
   go to :menuselection:`Accounting/Invoicing --> Settings --> Taxes --> EU Intra-community Distance
   Selling` and click on the :guilabel:`Refresh tax mapping`.

.. note::
   We highly recommend checking that the proposed mapping is suitable for the products and services
   you sell before using it.
>>>>>>> ff7204fb5 (temp)

.. seealso::
   - :doc:`../taxes`
   - :doc:`../../fiscal_localizations`
   - :doc:`fiscal_positions`

One-Stop Shop (OSS)
===================

The :abbr:`OSS (One-Stop Shop)` system introduced by the European Union simplifies VAT collection
for **cross-border** sales of goods and services. It primarily applies to business-to-consumer
**(B2C)** cases. With the OSS, businesses can register for VAT in their home country and use a
single online portal to handle VAT obligations for their sales within the EU. There are **two
primary schemes**: the **Union OSS** scheme for cross-border services and the **Import OSS** scheme
for goods valued at or below €150.

Reports
-------

To generate **OSS sales** or **OSS imports** reports and submit them onto the OSS portal, go to
:menuselection:`Accounting --> Reporting --> Tax Report`, click :guilabel:`Tax Report: Global
Summary`, and select either :guilabel:`OSS Sales` or :guilabel:`OSS Imports`. Once selected, click
on :guilabel:`PDF`, :guilabel:`XLSX`, or :guilabel:`XML` in the top-left corner. This generates the
currently-opened report in the selected format. Once generated, log into the platform of your
competent federal authority to submit it onto the OSS portal.

.. image:: eu_distance_selling/oss-report.png
   :alt: OSS reports view

.. seealso::
   - `European Commission: OSS | Taxation and Customs Union <https://ec.europa.eu/taxation_customs/business/vat/oss_en>`_
