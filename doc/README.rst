x-get a better wget
~~~~~~~~~~~~~~~~~~~

What in the world is this
=========================

I got frustrated at the slowness of regular `wget` due to it's single threaded nature.
Particuarly for taking backups of pages for preservation or offline reading purposes it's
particuarly infuriating, thus I decided to make this project.

This project first aims to being a pararell downloading tool for myself, but eventually I wish
to reimplement all of `wget` on go just for fun.

How do I get this going
=======================

The project is divided in two big parts, the general purpose library `github.com/a-villagra/xget`
and the unix commang `xget`, in order to install the command simply `go get` it.
