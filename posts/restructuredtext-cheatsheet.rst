.. title: restructuredText Cheatsheet
.. slug: restructuredtext-cheatsheet
.. date: 2014-07-02 21:38:50 UTC-03:00
.. tags: draft
.. link: 
.. description: 
.. type: text

1. numbers

A. upper-case letters
   and it goes over many lines

   with two paragraphs and all!

Huebadsa

.. TEASER_END

a. lower-case letters

   3. with a sub-list starting at a different number
   4. make sure the numbers are in the correct sequence though!

I. upper-case roman numerals

i. lower-case roman numerals

(1) numbers again

1) and again


* a bullet point using "*"

  - a sub-list using "-"

    + yet another sub-list

  - another item


what
  Definition lists associate a term with a definition.

*how*
  The term is a one-line phrase, and the definition is one or more
  paragraphs or body elements, indented relative to the term.
  Blank lines are not allowed between term and definition.


An example::

    Whitespace, newlines, blank lines, and all kinds of markup
      (like *this* or \this) is preserved by literal blocks.
  Lookie here, I've dropped an indentation level
  (but not far enough)

no more example


::

    This is preformatted text, and the
    last "::" paragraph is removed

Chapter 1 Title
===============

Section 1.1 Title
-----------------

Subsection 1.1.1 Title
~~~~~~~~~~~~~~~~~~~~~~

Section 1.2 Title
-----------------

Chapter 2 Title
===============


.. image:: /images/photo.jpeg

This is a paragraph.  It's quite
short.

   This paragraph will result in an indented block of
   text, typically used for quoting other text.

This is another one.


Simple table:

=====  =====  ====== 
   Inputs     Output 
------------  ------ 
  A      B    A or B 
=====  =====  ====== 
False  False  False 
True   False  True 
False  True   True 
True   True   True 
=====  =====  ======


.. code-block:: python
    :number-lines:

    import this

    print "it is useful"

.. youtube:: xa1Ie8-dQ9c

.. chart:: Bar
   :title: 'Browser usage evolution (in %)'
   :x_labels: ["2002", "2003", "2004", "2005", "2006", "2007"]

   'Firefox', [None, None, 0, 16.6, 25, 31]
   'Chrome',  [None, None, None, None, None, None]
   'IE',      [85.8, 84.6, 84.7, 74.5, 66, 58.6]
   'Others',  [14.2, 15.4, 15.3, 8.9, 9, 10.4]
