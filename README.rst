====================
cookiecutter-python3
====================
My Cookiecutter_ template for spinning up Python 3 semi-random projects. Contains (or will contain) all of the
various files and settings that I like to have for my Python 3 projects.

My plan is to create a series of these and then add them into my dotfiles scripts using the Cookiecutter python package.

Getting Started
---------------
* `GitHub Repo`_
* `Contributing Guidelines`_
* `Code of Conduct`_

Features
--------
Generates

- License file
- Authors file
- Readme file
- .gitignore
- .editorconfig

GitHub Templates

- Issue templates
- Pull request template
- Contributing documentation
- Code of Conduct documentation

Development
-----------
Makefile

* make bake - Bakes a copy of the cookiecutter into a .pantry folder for visual testing
* make clean - Cleans up the temporary .pantry folder


Usage
-----

CLI Usage:
    .. code-block:: bash

        $ cookiecutter gh:oakensoul/cookiecutter-python3

Python Usage:
    .. code-block:: python

        from cookiecutter.main import cookiecutter

        # Create project from the cookiecutter-oakensoul.git repo template
        cookiecutter('https://github.com/oakensoul/cookiecutter-python3.git')

Thanks & Credits
----------------

Thanks, and credit to `@audreyr`_ for creating the Cookiecutter_ command-line utility, which this project uses.

.. _`@audreyr`: https://github.com.com/audreyr
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`oakensoul/cookiecutter-python3`: https://github.com/oakensoul/cookiecutter-python3
.. _`GitHub Repo`: https://github.com/oakensoul/cookiecutter-oakensoul
.. _`Contributing Guidelines`: https://github.com/oakensoul/cookiecutter-python3/.github/CONTRIBUTING.md
.. _`Code of Conduct`: https://github.com/oakensoul/cookiecutter-python3/.github/CODE_OF_CONDUCT.md
