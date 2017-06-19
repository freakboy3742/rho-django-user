RHO Django User
===============

A "RKM's Humble Opinion" package for Django's Custom User model.

A custom Django user model that encompasses best practices:

* Email-based login

* "Full name"/"Short name", rather than the "First name"/"Last name"
   antipattern

Usage:
------

* Add `rhouser` to `INSTALLED_APPS`
* Add `AUTH_USER_MODEL="rhouser.User"` to your `settings.py` file.

To run tests:
-------------

Run::

    > python runtests.py
