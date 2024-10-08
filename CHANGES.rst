==============
Latest changes
==============

v0.1.4
======

:Date: 2024-09-14 (JST)

(Not featured release)

Misc
----

* Add classifier for python 3.12

v0.1.3
======

:date: 2023-10-26

(Not featured release)

Misc
----

* Fix to upload into GitHub Releases.
* Fix release-date of v0.1.2

v0.1.2
======

:date: 2023-10-26

Important
---------

* Rename from ``sphinx-sqlite3fts``

Fixes
-----

* Ref content-root when using Sphinx>=7.2

v0.1.1
======

:date: 2022-11-28

Small bug-fixes.

Fixes
-----

* Force override ``searchindex.js`` as blank file.
* ``searchtools.js`` initialize engine lazy.

v0.1.0
======

:date: 2022-11-27

For JavaScript based search-engine.

Features
--------

* Split sections from document for search (useful for refs of page).
* Add flag: search from database instead of Sphinx bundled search feature.

v0.0.3
======

:date: 2022-11-26

Update documents

Documentation
-------------

* Add badges into readme and documentation.
* Follow notes for v0.0.2

v0.0.2
======

:date: 2022-11-23

Supporting for local development.

Miscellaneous
-------------

* Use ``bump2version`` for release.
* Configure about line-length for ``pycodestyle``.

v0.0.1
======

:date: 2022-11-23

This is first release.

Features
--------

* Add ``sqlite`` builder that generate db.sqlite.
* Inject generator for database into ``html`` based builder.
