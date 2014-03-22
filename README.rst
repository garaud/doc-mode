
Emacs doc-mode
==============

A fork from `doc-mode <http://nschum.de/src/emacs/doc-mode/>`_. See also the
`source on Github https://github.com/nschum/doc-mode`_.

I looked for an alternative to the package doxymacs_ and I found
**doc-mode**. I'll try to make it work for Emacs 24. I'll try to keep the
backward compatibility with Emacs 23 but it's not warranty.

.. _doxymacs: http://doxymacs.sourceforge.net/

.. note::

   I'm an Emacs Lisp newbie. This modest project is an opportunity to write some
   Lisp code for Emacs and to have a proper management of Doxygen comments for
   my C++ code.

**doc-mode** allows easy creation and editing of JavaDoc or Doxygen comment
blocks in your code. It also greatly improves readability of code by folding the
blocks, so they don't take up precious screen lines.

Add the following to your ``.emacs`` file:

.. code-block:: lisp

   (require 'doc-mode)
   (add-hook 'c-mode-common-hook 'doc-mode)

The old current version 0.2 is available on Marmelade.
