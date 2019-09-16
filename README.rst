========================
How to use this skeleton
========================

Run::

    $ django-admin startproject --template *url or pathname* -e rst,cfg,txt *project name*

Where:

*url or pathname*
    either the url to the tarball
    (``https://github.com/Uninett/Uninett-django-project-skel/archive/master.zip``),
    or, if you've cloned the repo, the path to the repo
    (``/path/to/Uninett-django-project-skel``).

*project name*
    a python package name: same format as a python function name.

After having created the project boilerplate: 1) enter the *project name*
directory, 2) edit the README.rst inside and delete this paragraph and all
above it.

{% for char in project_name|make_list %}={% endfor %}==============
{{ project_name|title }} Documentation
{% for char in project_name|make_list %}={% endfor %}==============

Prerequisites
=============

* Python 3.5+
* pip
