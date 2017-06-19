RHO Django User
===============

A "Russell's Humble Opinion" Django Custom User model.

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

Run:

    > python runtests.py
