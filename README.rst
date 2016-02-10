StrManip
========

A tool for clipboard string manipulation in Python. You simply copy text
to the clipboard (or just select it if you have cutbuffer support) and
start the application. Works best when bound to a keyboard shortcut.

Once started, you can manipulate the string using Python expressions.
When finished, you can easily copy the text back to the clipboard.

Dependencies
~~~~~~~~~~~~

This tool requires the Kivy GUI application framework. For cutbuffer
support (X11 only), you will also need to install either xsel or xclip,
both of which are readily available on Ubuntu and similar distros.

Examples
~~~~~~~~

.. figure:: https://raw.githubusercontent.com/kived/strmanip/image-storage/filter-apt.png
   :alt: Filter Apt example

   Filter Apt example
