==============================
Synchronizing with KDE Kontact
==============================

KOrganizer and KAddressBook can synchronize your calendar, contacts and tasks with a Nextcloud server.

This can be done by following these steps:

1. Open KOrganizer and in the calendar list (bottom left) right-click and choose ``Add Calendar``:

.. image:: ../images/KOrganizer_add_calendar.png
   :alt:

2. In the resulting list of resources, pick ``DAV groupware resource``:

.. image:: ../images/korganizer_resource_choice.png
   :alt:

3. Enter your username. As password, you need to generate an app-password/token (`Learn more <https://docs.nextcloud.com/server/stable/user_manual/session_management.html#managing-devices>`_):

.. image:: ../images/korganizer_credentials.png
   :alt:

4. Choose ``ownCloud`` or ``Nextcloud`` as Groupware server option:

.. image:: ../images/KOrganizer_groupware_server.png
   :alt:

5. Enter your Nextcloud server URL and, if needed, installation path (anything that comes after the first /, for example ``mynextcloud`` in ``https://exampe.com/mynextcloud``). Then click next:

.. image:: ../images/KOrganizer_server_address.png
   :alt:

6. You can now test the connection, which can take some time for the initial connection. If it does not work, you can go back and try to fix it with other settings:

.. image:: ../images/KOrganizer_test1.png
   :alt:

.. image:: ../images/KOrganizer_test2.png
   :alt:

7. Pick a name for this resource, for example ``Work`` or ``Home``. By default, both CalDAV (Calendar) and CardDAV (Contacts) are synced:

.. image:: ../images/KOrganizer_pick_resources.png
   :alt:

.. note:: You can set a manual refresh rate for your calendar and contacts resources. By default this setting is set to 5 minutes and should be fine for the most use cases. When you create a new appointment it is synced to Nextcloud right away. You may want to change this for saving your power or cellular data plan, that you can update with a right-click on the item in the calendar list.

8. After a few seconds to minutes depending on your internet connection, you will find your calendars and contacts inside the KDE Kontact applications KOrganizer and KAddressBook:

.. image:: ../images/KOrganizer.png
   :alt:

.. image:: ../images/KAddressBook.png
   :alt:
