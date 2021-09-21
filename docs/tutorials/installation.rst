Installation Tutorial
=====================

.. note::

    For installation inside DLS, please see the internal documentation on
    ``dls-python3`` and ``pipenv``. Although these instructions will work
    inside DLS, they are intended for external use.

    If you want to contribute to the library itself, please follow
    the `contributing` instructions.


Check your version of python
----------------------------

You will need python 3.7 or later. You can check your version of python by
typing into a terminal::

    python3 --version


Create a virtual environment
----------------------------

It is recommended that you install into a “virtual environment” so this
installation will not interfere with any existing Python software::

    python3 -m venv /path/to/venv
    source /path/to/venv/bin/activate


Installing the library
----------------------

You can now use ``pip`` to install the library::

    python3 -m pip install sphinx_rtd_theme_github_versions

If you require a feature that is not currently released you can also install
from github::

    python3 -m pip install git+git://github.com/dls-controls/sphinx_rtd_theme_github_versions.git


Including in Sphinx Documentation
---------------------------------

Set the theme by declaring the `html_theme` in your ``conf.py`` file:

.. code-block:: python

    html_theme = "sphinx_rtd_theme_github_versions"

See `../how-to/configure-the-theme` for more details on configuring the theme