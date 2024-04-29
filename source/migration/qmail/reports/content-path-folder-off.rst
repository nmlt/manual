The maildir path does not point to ~/users/example
==================================================

``id:content-path-folder-off``

This error indicates that the qmail file contains a path to a maildir which is not a path to the corresponding maildir.

This bypasses the standard mailsetup and you need to check manually how to want to set this up.

.. include:: ../includes/levels/error.rst

auto migration
--------------

We will create a new standard mailbox for the corresponding mailuser and collect new incoming mails there. The redirect
to the custom mailbox will no longer work but any files will be synced to your new Asteroid so you might be able to
restore older mails from there.

.. include:: ../includes/auto-migration.rst