=====
Usage
=====

To use Django Scheduled Task in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'dj_scheduled_task.apps.DjScheduledTaskConfig',
        ...
    )

Add Django Scheduled Task's URL patterns:

.. code-block:: python

    from dj_scheduled_task import urls as dj_scheduled_task_urls


    urlpatterns = [
        ...
        url(r'^', include(dj_scheduled_task_urls)),
        ...
    ]
