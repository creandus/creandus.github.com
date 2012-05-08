---
title: Creandus
---

Creandus
========

Creandus began as a project for Google's Summer of Code in 2006. It aims to
provide a simple interface for package managers to manage users added for
specific packages. Hooks are available for the Paludis package manager, and it
is easy enough to hook into your package manager, using the Creandus API
Documentation.

What is Creandus?
=================

Creandus is an implementation of Gentoo's GLEP 27. It is meant to replace the
enewuser and enewgroup functions. While it was written for Gentoo, it would be
very easy to extend it to any other distribution -- the only thing it really
needs is bash.

Why use Creandus?
=================

Implementing GLEP 27 will allow for a more automated approach to adding users
with ebuilds in more cases. This will help the overall security of the Gentoo
rise, as it will be easier for every daemon to run as its own limited user,
reducing the risk of a security flaw in a daemon from causing damage to a
system. Also, adding this level of automation will add a level of polish to the
Gentoo distribution.

This project could be generalized to work with other package management systems
in other distributions, so that they can also have dynamically-assigned
UIDs/GIDs for package-specific users/groups and not have to worry about
maintaining a list of officially assigned numbers.

Contributing
============

If you would like to contribute, a ticket is probably the best way to go. But,
you'll have to register first. Also, the project roadmap has a list of tickets
that need attention.
