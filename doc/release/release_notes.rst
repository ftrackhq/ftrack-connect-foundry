..
    :copyright: Copyright (c) 2015 ftrack

.. _release/release_notes:


*************
Release notes
*************

.. release:: 2.0.0
    :date: 2020-11-12

   ..change:: changed
        :tags: API

        Use ftrack `connector legacy repository <https://bitbucket.org/ftrack/ftrack-connector-legacy>`_ in place of ftrack-connect.


.. release:: 1.2.1
    :date: 2019-11-15

    ..change:: fix
        :tags: Browse

        Error on string encoding while importing published scripts on windows.

.. release:: 1.2.0
    :date: 2018-12-19

    .. change:: changed
        :tags: internal

        Remove ftrack-connect dependency.

.. release:: 1.1.1
    :date: 2018-04-27
    .. change:: fixed
        :tags: API

        Not all the code has been ported to PySide2.

.. release:: 1.1.0
    :date: 2017-09-12

    .. change:: fixed
        :tags: API

        Nuke 11 not supported.


.. release:: 1.0.0
    :date: 2017-07-07

    .. change:: change
        :tags: API

        The Connect Foundry integration has changed to use the `ftrack-python-api`
        instead of the `legacy api`. Since custom locations are not compatible between
        the different APIs all users running from source with custom locations for
        the `legacy api` must either:

        #.  Use the
            `Location compatibility layer <https://bitbucket.org/ftrack/ftrack-location-compatibility/>`_
            by putting it's resource folder on the `FTRACK_EVENT_PLUGIN_PATH`.
        #.  Or, re-write the location using the `ftrack-python-api`.

        for more information about the migration process please look at the main `ftrack-connect`
        `Documentation <http://ftrack-connect.rtd.ftrack.com/en/latest/release/migration.html>

 
    .. change:: new
        :tags: Build track, User interface

        Added checkbox to build track from nuke scripts.

.. release:: 0.1.0
    :date: 2015-03-18

    .. change:: new
        :tags: Browse, User interface

        Added header from ftrack connect to browse window.
