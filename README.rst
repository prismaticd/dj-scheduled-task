=============================
Django Scheduled Task
=============================

.. image:: https://badge.fury.io/py/dj-scheduled-task.svg
    :target: https://badge.fury.io/py/dj-scheduled-task

.. image:: https://travis-ci.org/prismaticd/dj-scheduled-task.svg?branch=master
    :target: https://travis-ci.org/prismaticd/dj-scheduled-task

.. image:: https://codecov.io/gh/prismaticd/dj-scheduled-task/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/prismaticd/dj-scheduled-task

A Django library to run background task (Cron Style) with a DB backend

Documentation
-------------

The full documentation is at https://dj-scheduled-task.readthedocs.io.

Quickstart
----------

Install Django Scheduled Task::

    pip install dj-scheduled-task

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'dj_scheduled_task.apps.DjScheduledTaskConfig',
        ...
    )



Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
