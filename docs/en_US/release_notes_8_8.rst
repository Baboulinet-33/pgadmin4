***********
Version 8.8
***********

Release date: 2024-06-27

This release contains a number of bug fixes and new features since the release of pgAdmin 4 v8.7.

Supported Database Servers
**************************
**PostgreSQL**: 12, 13, 14, 15, and 16

**EDB Advanced Server**: 12, 13, 14, 15, and 16

Bundled PostgreSQL Utilities
****************************
**psql**, **pg_dump**, **pg_dumpall**, **pg_restore**: 16.3


New features
************


Housekeeping
************


Bug fixes
*********

  | `Issue #5785 <https://github.com/pgadmin-org/pgadmin4/issues/5785>`_ -  Fix an issue where user authentication fails with special characters in password.
  | `Issue #7480 <https://github.com/pgadmin-org/pgadmin4/issues/7480>`_ -  Fixed an issue where canceling a query without privilege does not display any message on query tool.