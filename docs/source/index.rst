.. _Naglowek tekstowy poziomu 1:
Nagłówek tekstowy poziomu 1
============================

============================
Nagłówek tekstowy poziomu 2
============================

Nagłówek tekstowy poziomu 3
----------------------------

Naglówek tekstowy poziomu 4
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Akapit tekstowy

.. Note::
   akapit informacyjny typu note

.. tip::
   akapit informacyjny typu tip

:code:`println!("Hello World - Fragmentowy");`

..  code-block:: php
    :caption: EXT:site_package/Configuration/TCA/Overrides/sys_template.php

    /**
     * Add default TypoScript (constants and setup)
     */
    \TYPO3\CMS\Core\Utility\ExtensionManagementUtility::addStaticFile(
         'site_package',
         'Configuration/TypoScript',
         'Site Package'
    );

:ref:`Naglowek tekstowy poziomu 1`

`link description <https://www.writethedocs.org/guide/writing/reStructuredText/>`_

Lista numerowana
----------------------------
#. first item
#. second item

Lista wypunktowana
----------------------------
*  Item
*  Item
*  Item

.. image:: ./goat123.jpg
               :alt: Text describing the image

.. list-table:: Tabela stworzona w języku RST
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

Contents
--------

.. toctree::

   usage
   api
