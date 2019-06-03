{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
{{ cookiecutter.project_name }}
===============================

{% if is_open_source %}

[![Pypi][pypi]](https://pypi.python.org/pypi/{{ cookiecutter.project_slug }})
[![Travis build][travis]](https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }})
[![Read the docs][rtfm]](https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io/en/latest/?badge=latest)

{%- endif %}

[![Pyup][pyup]](https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/)

{{ cookiecutter.project_short_description }}

{% if is_open_source %}
* Free software: {{ cookiecutter.open_source_license }}
* Documentation: https://{{ cookiecutter.github_username }}.github.io.{{ cookiecutter.project_slug}}
{% endif %}

Features
--------

* TODO

[pypi]: https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg
[travis]: https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg
[rtfm]: https://{{ cookiecutter.github_username }}.github.io.{{ cookiecutter.project_slug}}
[pyup]: https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/shield.svg
