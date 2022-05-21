===================
pytest-scipydoctest
===================

.. image:: https://img.shields.io/pypi/v/pytest-scipydoctest.svg
    :target: https://pypi.org/project/pytest-scipydoctest
    :alt: PyPI version

.. image:: https://img.shields.io/pypi/pyversions/pytest-scipydoctest.svg
    :target: https://pypi.org/project/pytest-scipydoctest
    :alt: Python versions

.. image:: https://ci.appveyor.com/api/projects/status/github/ev-br/pytest-scipydoctest?branch=master
    :target: https://ci.appveyor.com/project/ev-br/pytest-scipydoctest/branch/master
    :alt: See Build Status on AppVeyor

Doctests on steroids

----

This `pytest`_ plugin was generated with `Cookiecutter`_ along with `@hackebrot`_'s `cookiecutter-pytest-plugin`_ template.


Features
--------


Clone the repo and pip install it::


    $ pip install .

Test-drive::

    $ cd tests
    $ pytest -pno:doctest --doctest-modules  mod.py -v -s

Here ``mod.py`` is simply::


    def func():
        """
        >>> 2 / 3
        0.667
        """
        pass

Note that the doctest passes, even though it fails with the vanilla doctest module.


Requirements
------------

* TODO


Installation
------------

You can install "pytest-scipydoctest" via `pip`_ from `PyPI`_::

    $ pip install pytest-scipydoctest


Usage
-----

* TODO

Contributing
------------
Contributions are very welcome. Tests can be run with `tox`_, please ensure
the coverage at least stays the same before you submit a pull request.

License
-------

Distributed under the terms of the `BSD-3`_ license, "pytest-scipydoctest" is free and open source software


Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`Cookiecutter`: https://github.com/audreyr/cookiecutter
.. _`@hackebrot`: https://github.com/hackebrot
.. _`MIT`: http://opensource.org/licenses/MIT
.. _`BSD-3`: http://opensource.org/licenses/BSD-3-Clause
.. _`GNU GPL v3.0`: http://www.gnu.org/licenses/gpl-3.0.txt
.. _`Apache Software License 2.0`: http://www.apache.org/licenses/LICENSE-2.0
.. _`cookiecutter-pytest-plugin`: https://github.com/pytest-dev/cookiecutter-pytest-plugin
.. _`file an issue`: https://github.com/ev-br/pytest-scipydoctest/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`tox`: https://tox.readthedocs.io/en/latest/
.. _`pip`: https://pypi.org/project/pip/
.. _`PyPI`: https://pypi.org/project
