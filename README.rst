CMS Forms
==================
|Pypi|

A plug-and-play form management plugin for your CMS project,
that lets you create and manage forms effortlessly.

This plugin is **only intended to be used with a CMS project**,
and not directly in any django project. To use in an independent
django project, you might need to configure your project.


Features
------------
- Plug & Play GraphQL-based APIs
- Forms with slot selection/filling support
- Support for custom field types, validation methods etc.

Installation
------------

1. Install last stable version from Pypi:

::

    pip install cms-forms

2. Add ``forms`` app into your *INSTALLED_APPS* settings:

.. code:: python

    INSTALLED_APPS = [
        ...
        'forms'
        ...
    ]

3. Add schemas of ``forms`` app into ``schema.py`` in your
project folder, for the APIs to work.

4. Make migrations, and migrate changes.


.. |Pypi| image:: https://img.shields.io/pypi/v/cms-forms.svg
   :target: https://pypi.python.org/pypi/cms-forms
   :alt: Pypi


