Arch Linux OpenRC Services
==========================

OpenRC_ service files for `Arch Linux`_.

Submitting Service Files
------------------------

Be sure to follow the following guidelines before submitting service files.

* Instead of duplicating effort, search for service files in Gentoo's repositories_. If you do find them, they will need to be adjusted for use with Arch, as mentioned in the following steps.
* Make sure pid files are created under :code:`/run` instead of :code:`/var/run`.
* With Arch Linux having finished the `/usr unification`_, ensure that the service files are adjusted accordingly.
* Include respective conf files where necessary.
* Use 4 spaces for indentation.
* Make a single commit per service.
* Ensure that the service files actually work ;)

See :code:`man runscript` for help with writing service files.

.. _OpenRC: https://wiki.gentoo.org/wiki/Project:OpenRC
.. _Arch Linux: https://www.archlinux.org/
.. _repositories: http://sources.gentoo.org/cgi-bin/viewvc.cgi
.. _/usr unification: https://lwn.net/Articles/483921/
