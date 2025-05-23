Python Prompt Toolkit 3.0
=========================

`prompt_toolkit` is a library for building powerful interactive command line
and terminal applications in Python.


It can be a very advanced pure Python replacement for `GNU readline
<https://tiswww.case.edu/php/chet/readline/rltop.html>`_, but it can also be
used for building full screen applications.

.. image:: images/ptpython-2.png

Some features:

- Syntax highlighting of the input while typing. (For instance, with a Pygments lexer.)
- Multi-line input editing.
- Advanced code completion.
- Selecting text for copy/paste. (Both Emacs and Vi style.)
- Mouse support for cursor positioning and scrolling.
- Auto suggestions. (Like `fish shell <http://fishshell.com/>`_.)
- No global state.

Like readline:

- Both Emacs and Vi key bindings.
- Reverse and forward incremental search.
- Works well with Unicode double width characters. (Chinese input.)

Works everywhere:

- Pure Python. Runs on all Python versions starting at Python 3.6.
  (Python 2.6 - 3.x is supported in prompt_toolkit 2.0; not 3.0).
- Runs on Linux, OS X, OpenBSD and Windows systems.
- Lightweight, the only dependencies are Pygments and wcwidth.
- No assumptions about I/O are made. Every prompt_toolkit application should
  also run in a telnet/ssh server or an `asyncio
  <https://docs.python.org/3/library/asyncio.html>`_ process.

Have a look at :ref:`the gallery <gallery>` to get an idea of what is possible.

Getting started
---------------

Go to :ref:`getting started <getting_started>` and build your first prompt. 
Issues are tracked `on the Github project
<https://github.com/prompt-toolkit/python-prompt-toolkit>`_.


Thanks to:
----------

A special thanks to `all the contributors
<https://github.com/prompt-toolkit/python-prompt-toolkit/graphs/contributors>`_
for making prompt_toolkit possible.

Also, a special thanks to the `Pygments <http://pygments.org/>`_ and `wcwidth
<https://github.com/jquast/wcwidth>`_ libraries.


Table of contents
-----------------

.. toctree::
   :maxdepth: 2

   pages/gallery
   pages/getting_started
   pages/upgrading/index
   pages/printing_text
   pages/asking_for_input
   pages/dialogs
   pages/progress_bars
   pages/full_screen_apps
   pages/tutorials/index
   pages/advanced_topics/index
   pages/reference
   pages/related_projects


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Prompt_toolkit was created by `Jonathan Slenders
<http://github.com/prompt-toolkit/>`_.
