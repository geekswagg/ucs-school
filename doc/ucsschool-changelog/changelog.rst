.. SPDX-FileCopyrightText: 2021-2024 Univention GmbH
..
.. SPDX-License-Identifier: AGPL-3.0-only

.. _changelog-changelogs:

*********
Changelog
*********

.. _changelog-ucsschool-2025-XX-XX:

Released on 2025-04-03
======================

Source package *ucs-school-umc-exam* in version ``10.0.16``:

* Fixed a bug for students in multiple exams, if the :envvar:`ucsschool/exam/user/disable` was set to ``yes``.
  Their exam users would not be configured properly (:uv:bug:`58116`).


.. _changelog-ucsschool-2025-03-10:

Released on 2025-03-10
======================

Source package *ucs-school-metapackage* in version ``13.0.19``:

* Updated: In preparation for the UCS@school 5.2 update, two join hooks are now installed in the system. The first uses Python 2.7 and is registered for UCS 4.4 systems only. The second uses Python 3 and is registered in the LDAP for UCS 5.0 and newer (:uv:bug:`57897`).

Source package *ucs-school-import-lusd* in version ``1.0.5``:

* Fixed: The default value for the LUSD ``issuer``, used for authentication, has been changed for production use (:uv:bug:`57974`).
