Installation
============

Stable release
--------------

To install {{ cookiecutter.project_name }}, run this command in your terminal:

```
$ pip install {{ cookiecutter.project_slug }}
```

This is the preferred method to install {{ cookiecutter.project_name }}, as it will always install the most recent stable release.

If you don't have [pip][pip] installed, this [Python installation guide][python] can guide
you through the process.


From sources
------------

The sources for {{ cookiecutter.project_name }} can be downloaded from the [Github repo][repo].

You can either clone the public repository:

```
$ git clone git://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
```

Or download the [tarball][tarball]:

```
$ curl  -OL https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
```

Once you have a copy of the source, you can install it with [Poetry][poetry]:

```
$ poetry install
```

[pip]: https://pip.pypa.io
[python]: http://docs.python-guide.org/en/latest/starting/installation/
[repo]: https://github.com/maebert/mazuma
[tarball]: https://github.com/maebert/mazuma/tarball/master
[poetry]: https://poetry.eustace.io/
