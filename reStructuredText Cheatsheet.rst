
**********
Paragraphs
**********

Para 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

 Para 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Para 3.

=============
Inline Markup
=============

*Italics*

:emphasis:`emphasis`

**Emphasis/Bold**

:strong:`strong`

`hello`

``code samples``

:literal:`literal`

A :subscript:`subscript`

A :superscript:`superscript`

:title-reference:`title-reference`

===========================
Lists and Quote-like blocks
===========================

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.

Nested Lists
------------
* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues

Definition Lists
----------------
term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

Quoted Paragraphs
^^^^^^^^^^^^^^^^^
  Quoted Paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Line Blocks
^^^^^^^^^^^
| These lines are
| broken exactly like in
| the source file.

Source Code
-----------
This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

.. _tables-link:

Tables
------
Grid Tables
^^^^^^^^^^^
+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

Simple Tables
^^^^^^^^^^^^^
=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

CSV Tables
^^^^^^^^^^
.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

List Table
^^^^^^^^^^
.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!

==========
Hyperlinks
==========

.. _my-reference-label:

External Links
--------------
`Online reStructuredText editor <http://rst.ninjs.org>`_

This is a paragraph that contains a link to the `online rst editor`_.

.. _online rst editor: http://rst.ninjs.org

Internal Links
--------------

See :ref:`tables-link`

It refers to the section itself, see :ref:`my-reference-label`.

========
Sections
========

The area of a circle is :math:`A_\text{c} = (\pi/4) d^2`.

See :PEP:`287` for more information about reStructuredText.

See :RFC:`2822` for information about email headers.
