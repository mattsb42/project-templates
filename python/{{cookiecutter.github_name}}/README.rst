{%for i in cookiecutter.pypi_name %}#{% endfor %}
{{cookiecutter.pypi_name}}
{%for i in cookiecutter.pypi_name %}#{% endfor %}

.. image:: https://img.shields.io/pypi/v/{{cookiecutter.pypi_name}}.svg
   :target: https://pypi.python.org/pypi/{{cookiecutter.pypi_name}}
   :alt: Latest Version

.. image:: https://img.shields.io/pypi/pyversions/{{cookiecutter.pypi_name}}.svg
   :target: https://pypi.python.org/pypi/{{cookiecutter.pypi_name}}
   :alt: Supported Python Versions

.. image:: https://img.shields.io/badge/code_style-black-000000.svg
   :target: https://github.com/ambv/black
   :alt: Code style: black

.. image:: https://readthedocs.org/projects/{{cookiecutter.pypi_name}}/badge/
   :target: https://{{cookiecutter.pypi_name}}.readthedocs.io/en/stable/
   :alt: Documentation Status

.. image:: https://travis-ci.org/awslabs/{{cookiecutter.pypi_name}}.svg?branch=master
   :target: https://travis-ci.org/awslabs/{{cookiecutter.pypi_name}}
   :alt: Travis CI Test Status

.. image:: https://ci.appveyor.com/api/projects/status/REPLACEME/branch/master?svg=true
   :target: https://ci.appveyor.com/project/REPLACEME
   :alt: AppVeyor Test Status

.. important::

    This project is a work in progress and is not yet ready for use.

{{cookiecutter.project_description}}
