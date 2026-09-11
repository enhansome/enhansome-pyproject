# Awesome pyproject.toml with stars

![logo](https://repository-images.githubusercontent.com/226840558/aff71800-2fd4-11ea-99ed-8e6a645dd5fe)

`pyproject.toml` is a new configuration file defined in
[PEP 518](https://www.python.org/dev/peps/pep-0518/), expanded in
[PEP 621](https://www.python.org/dev/peps/pep-0621/) and
[PEP 660](https://www.python.org/dev/peps/pep-660/). It is design to store
build system requirements, but it can also store any tool configuration for your
Python project, possibly replacing the need for `setup.cfg` or other
tool-specific files.

* [PEP 518 -- File specification](https://www.python.org/dev/peps/pep-0518/#specification).
* [PEP 621 -- Storing project metadata in pyproject.toml](https://www.python.org/dev/peps/pep-0621/#specification)
* [PEP 660 -- Editable installs for pyproject.toml based builds (wheel based)](https://peps.python.org/pep-0660/)

We think `pyproject.toml` is pretty awesome, so this
[awesome list](https://github.com/topics/awesome-list) contains projects already
using it, or discussing its inclusion.

Do you know of any other project not included here? Please
[submit a PR](contributing.md)!

## Contents

* [Testing](#testing)
* [Code Formatting](#code-formatting)
* [Code Analysis](#code-analysis)
* [Packaging & Project Management](#packaging--project-management)
* [Project Templates](#project-templates)
* [Other Tools](#other-tools)
* [Articles](#articles)
* [Open PEPs](#open-peps)
* [Projects discussing the use of pyproject.toml](#projects-discussing-the-use-of-pyprojecttoml)

## Testing

* [ptr](https://github.com/facebookincubator/ptr#pyprojecttoml) ⚠️ Archived - Python Test Runner (ptr) was born to run tests in an opinionated way, within arbitrary code repositories.
* [pytest-env](https://github.com/pytest-dev/pytest-env) ⭐ 236 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - A pytest plugin that enables you to set environment variables in a pyproject.toml file.
* [Coverage.py](https://coverage.readthedocs.io/en/latest/config.html) - Code coverage measurement for Python.
* [pytest](https://docs.pytest.org/en/latest/reference/customize.html#pyproject-toml) - A testing framework that makes it easy to write small tests, yet scales to support complex functional testing.
* [Tox](https://tox.readthedocs.io/en/3.14.2/example/basic.html#pyproject-toml-tox-legacy-ini) - A generic virtualenv manager to run test in different environments.
* [Ward](https://ward.readthedocs.io/en/latest/guide/pyproject.toml.html) - A modern Python test framework designed to help you find and fix flaws faster.

## Code Formatting

* [YAPF](https://github.com/google/yapf#excluding-files-from-formatting-yapfignore-or-pyprojecttoml) ⭐ 13,984 | 🐛 422 | 🌐 Python | 📅 2026-08-28 - A formatter for Python files.
* [autopep8](https://github.com/hhatto/autopep8/blob/master/README.rst#pyproject-toml) ⭐ 4,660 | 🐛 135 | 🌐 Python | 📅 2026-07-20 - A tool that automatically formats Python code to conform to the PEP 8 style guide.
* [autoflake](https://github.com/PyCQA/autoflake) ⭐ 952 | 🐛 43 | 🌐 Python | 📅 2026-08-23 - Removes unused imports and unused variables as reported by pyflakes.
* [Darker](https://github.com/akaihola/darker#customizing-darker-black-and-isort-behavior) ⭐ 685 | 🐛 47 | 🌐 Python | 📅 2025-10-22 - Apply black reformatting to Python files only in regions changed since a given commit.
* [flake8-isort](https://github.com/gforcada/flake8-isort/commit/701995ab1f401e6f64c58ce2cb58756216d2e8a2) ⭐ 186 | 🐛 1 | 🌐 Python | 📅 2025-10-25 - flake8 plugin that integrates isort.
* [autoimport](https://lyz-code.github.io/autoimport/) - Automatically add missing imports and remove unused imports.
* [Black](https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html#configuration-via-a-file) - The uncompromising Python code formatter.
* [Blue](https://blue.readthedocs.io/en/latest/) - The slightly less uncompromising Python code formatter.
* [isort](https://pycqa.github.io/isort/docs/configuration/options) - A Python utility / library to sort imports alphabetically, and automatically separated into sections.
* [pyproject-fmt](https://pyproject-fmt.readthedocs.io) - Apply a consistent format to your pyproject.toml file with comment support.

## Code Analysis

* [Pyright](https://github.com/microsoft/pyright/blob/1.1.200/docs/configuration.md#sample-pyprojecttoml-file) ⭐ 15,632 | 🐛 326 | 🌐 Python | 📅 2026-09-10 - Static type checker for Python.
* [Vulture](https://github.com/jendrikseipp/vulture/blob/master/README.md#configuration) ⭐ 4,806 | 🐛 71 | 🌐 Python | 📅 2026-04-30 - Finds unused code in Python programs.
* [Refurb](https://github.com/dosisod/refurb) ⭐ 2,532 | 🐛 33 | 🌐 Python | 📅 2026-04-03 - A tool for refurbishing and modernizing Python codebases.
* [deptry](https://github.com/fpgmaas/deptry) ⭐ 1,477 | 🐛 68 | 🌐 Python | 📅 2026-09-10 - A command line tool to check for issues with dependencies in a Python project, such as obsolete or missing dependencies.
* [Unimport](https://github.com/hakancelik96/unimport/blob/master/README.md#configuring-unimport) ⭐ 247 | 🐛 1 | 🌐 Python | 📅 2026-06-02 - Detects unused python libraries.
* [pytest-pylint](https://github.com/carsongee/pytest-pylint/pull/107) ⭐ 77 | 🐛 12 | 🌐 Python | 📅 2024-04-13 - A pytest plugin for running pylint against your codebase.
* [Bandit](https://bandit.readthedocs.io/en/latest/config.html) - A tool designed to find common security issues in Python code.
* [FlakeHell](https://flakehell.readthedocs.io/config.html) - Flake8 wrapper to make it nice, legacy-friendly, configurable.
* [flake8-pyproject](https://pypi.org/project/Flake8-pyproject/) - Plugin for Flake8 that reads configuration from pyproject.toml and injects the config into Flake8
* [import-linter](https://import-linter.readthedocs.io/en/stable/usage.html) - Import Linter defines and enforces rules for the imports within and between Python packages.
* [interrogate](https://interrogate.readthedocs.io/en/latest/#other-usage) - Interrogate a codebase for docstring coverage.
* [Mypy](https://mypy.readthedocs.io/en/latest/config_file.html#using-a-pyproject-toml-file) - An optional static type checker for Python (PEP 484).
* [Nitpick](https://nitpick.readthedocs.io/en/latest/configuration.html) - Flake8 plugin to enforce the same tool configuration (flake8, isort, mypy, Pylint...) across multiple Python projects.
* [pydocstyle](https://www.pydocstyle.org/en/stable/usage.html#configuration-files) - A static analysis tool for checking compliance with Python docstring conventions.
* [Pylint](http://pylint.pycqa.org/en/latest/user_guide/run.html?highlight=pyproject#command-line-options) - A tool that checks for errors in Python code, tries to enforce a coding standard and looks for code smells.
* [Robocop](https://robocop.readthedocs.io/en/stable/configuration.html#pyproject-toml-or-toml-configuration-file) - Tool for static code analysis of Robot Framework language.
* [rstcheck](https://rstcheck.readthedocs.io/en/latest/usage/config/#toml-format) - Checks syntax of reStructuredText and code blocks nested within it.
* [Ruff](https://beta.ruff.rs/docs/configuration/#pyprojecttoml-discovery) - An extremely fast Python linter, written in Rust.
* [validate-pyproject](https://validate-pyproject.readthedocs.io) - A command line tool and Python library for validating pyproject.toml files based on JSON Schema, and includes checks for PEP 517, PEP 518 and PEP 621.
* [wemake-python-styleguide](https://wemake-python-styleguide.readthedocs.io/en/latest/pages/usage/integrations/flakeheaven.html) - The strictest and most opinionated python linter ever!

## Packaging & Project Management

* [Maturin](https://github.com/PyO3/maturin/blob/main/README.md#python-metadata) ⭐ 5,788 | 🐛 57 | 🌐 Rust | 📅 2026-09-09 - Build and publish crates with pyo3, rust-cpython and cffi bindings as well as rust binaries as python packages.
* [Pyflow](https://github.com/David-OConnor/pyflow) ⭐ 1,338 | 🐛 62 | 🌐 Rust | 📅 2026-03-21 - An installation and dependency system for Python.
* [setuptools\_scm](https://github.com/pypa/setuptools_scm) ⭐ 952 | 🐛 23 | 🌐 Python | 📅 2026-09-07 - Handles managing your Python package versions in SCM metadata instead of declaring them as the version argument or in a SCM managed file.
* [FawltyDeps](https://github.com/tweag/FawltyDeps) ⭐ 289 | 🐛 89 | 🌐 Python | 📅 2025-07-01 - Find undeclared and unused dependencies in your Python project. Verify that your declared dependencies (in `pyproject.toml` or elsewhere) match what you actually `import` in your code.
* [check-wheel-contents](https://github.com/jwodder/check-wheel-contents) ⭐ 168 | 🐛 34 | 🌐 Python | 📅 2026-07-20 - Check your wheels have the right contents.
* [BeeWare Briefcase](https://briefcase.readthedocs.io/en/latest/reference/configuration.html) - Tools to support converting a Python project into a standalone native application.
* [DepHell](https://dephell.readthedocs.io/config.html) - Project management for Python. Manage packages: convert between formats, lock, install, resolve, isolate, test, build graph, show outdated, audit. Manage venvs, build package, bump version.
* [Flit](https://flit.readthedocs.io/en/stable/pyproject_toml.html) - A simple way to put Python packages and modules on PyPI.
* [Hatch](https://hatch.pypa.io/latest/config/metadata/) - Modern, extensible Python project manager.
* [PDM](https://pdm.fming.dev/latest/pyproject/pep621/) - A modern Python package manager with PEP 582 support.
* [pip](https://pip.pypa.io/en/stable/reference/pip/#pep-517-and-518-support) - The package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.
* [Poetry](https://python-poetry.org/docs/pyproject/) - A tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.
* [setuptools](hhttps://setuptools.pypa.io/en/latest/userguide/pyproject_config.html) - Easily download, build, install, upgrade, and uninstall Python packages.

## Project Templates

Python project templates or project generators supporting `pyproject.toml`.

* [PyPA Sample Project](https://github.com/pypa/sampleproject) ⭐ 5,241 | 🐛 24 | 🌐 Python | 📅 2024-11-06 - A sample project that exists for PyPUG's "Tutorial on Packaging and Distributing Projects".
* [wemake-django-template](https://github.com/wemake-services/wemake-django-template) ⭐ 2,270 | 🐛 21 | 🌐 Python | 📅 2026-09-09 - Bleeding edge django template focused on code quality and security.
* [PyScaffold](https://github.com/pyscaffold/pyscaffold) ⭐ 2,261 | 🐛 37 | 🌐 Python | 📅 2026-08-31 - Python project template generator with batteries included.
* [Hypermodern Cookiecutter](https://github.com/cjolowicz/cookiecutter-hypermodern-python) ⭐ 1,920 | 🐛 105 | 🌐 Python | 📅 2024-05-18 - Cookiecutter template for a Python package based on the [Hypermodern Python](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/) article series.
* [cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary) ⭐ 1,299 | 🐛 11 | 🌐 Python | 📅 2026-04-08 - Cookiecutter template for a Python python library.
* [Python Packages Project Generator](https://github.com/TezRomacH/python-package-template) ⚠️ Archived - Cookiecutter template with state-of-the-art libraries and best development practices for Python.
* [Jace's Python Template](https://github.com/jacebrowning/template-python) ⭐ 668 | 🐛 7 | 🌐 Python | 📅 2025-03-20 - A template for new Python libraries.
* [wemake-python-package](https://github.com/wemake-services/wemake-python-package) ⭐ 446 | 🐛 4 | 🌐 Python | 📅 2026-09-07 - Bleeding edge cookiecutter template to create new python packages.
* [cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry) ⭐ 426 | 🐛 14 | 🌐 Python | 📅 2024-10-02 - A modern cookiecutter template for Python projects that use Poetry for their dependency management.
* [Poetry Cookiecutter](https://github.com/radix-ai/poetry-cookiecutter) ⭐ 374 | 🐛 16 | 🌐 Jinja | 📅 2026-08-19 - A modern Cookiecutter template for scaffolding Python packages and apps.
* [Tyrannosaurus](https://github.com/dmyersturnbull/tyrannosaurus) ⭐ 93 | 🐛 16 | 🌐 Python | 📅 2023-10-10 - An opinionated, 2021+ Python template and project generator with many integrations and an automated CI/CD workflow triggered only through Git and GitHub.

## Other Tools

* [Poe the Poet](https://github.com/nat-n/poethepoet#define-tasks-in-your-pyprojecttoml) ⭐ 2,073 | 🐛 13 | 🌐 Python | 📅 2026-07-12 - A task runner that works well with Poetry.
* [towncrier](https://github.com/twisted/towncrier) ⭐ 921 | 🐛 68 | 🌐 Python | 📅 2026-09-08 - A utility to produce useful, summarised news files for your project.
* [zsh-autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv/pull/117) ⭐ 636 | 🐛 34 | 🌐 Shell | 📅 2026-02-07 - ZSH plugin to automatically switch python virtualenvs and Pipenvs as you move between directories.
* [Autohooks](https://github.com/greenbone/autohooks/blob/master/README.md#1-choosing-an-autohooks-mode) ⭐ 206 | 🐛 3 | 🌐 Python | 📅 2026-09-07 - Library for managing git hooks.
* [Python License Checker](https://github.com/dhatim/python-license-check/pull/32) ⭐ 184 | 🐛 28 | 🌐 Python | 📅 2026-07-20 - Check python packages from requirement.txt/pyproject.toml and report issues.
* [Poetrify](https://github.com/kk6/poetrify) ⚠️ Archived - Convert a Pipfile (or requirements.txt) to pyproject.toml for Poetry.
* [poetry-setup](https://github.com/orsinium/poetry-setup) ⚠️ Archived - Generate setup.py (setuptools) from pyproject.toml.
* [Vendy](https://github.com/di/vendy) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2023-11-28 - A tool for vendoring third-party packages into your project.
* [poetry-version](https://github.com/rominf/poetry-version) ⚠️ Archived - Python library for extracting version from poetry pyproject.toml file.
* [django-pyproject](https://github.com/Ceterai/django-pyproject) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-04-21 - Django package to store some or all of your settings in your pyproject.toml file.
* [Commitizen](https://commitizen-tools.github.io/commitizen/config/) - Create commiting rules for projects, auto bump versions and auto changelog generation.
* [datamodel-code-generator](https://koxudaxi.github.io/datamodel-code-generator/pyproject_toml/) - Creates Pydantic data-model code from OpenAPI/JSON Schema files.
* [ini2toml](https://ini2toml.readthedocs.io/en/latest/setuptools_pep621.html) - Automatically translates .ini/.cfg files into TOML.
* [Tartufo](https://tartufo.readthedocs.io/en/latest/configuration.html#configuration-via-file) - Searches through git repositories and their history for high entropy strings and secrets.

## Articles

* [Clarifying PEP 518 (a.k.a. pyproject.toml)](https://snarky.ca/clarifying-pep-518/)
* [pyproject.toml Reference - Python Developer Tooling Handbook](https://pydevtools.com/handbook/reference/pyproject.toml/) - A reference guide to pyproject.toml covering its role in Python packaging, key sections, and how tools use it.
* [What the heck is pyproject.toml?](https://snarky.ca/what-the-heck-is-pyproject-toml/)

## Open PEPs

Python Enhancement Proposals (PEPs) still under consideration related to pyproject.toml.

* [PEP 725 – Specifying external dependencies in pyproject.toml](https://peps.python.org/pep-0725/)
* [PEP 735 – Dependency Groups in pyproject.toml](https://peps.python.org/pep-0735/)

### Rejected/Withdrawn/Superseded

* [PEP 631 – Dependency specification in pyproject.toml based on PEP 508](https://www.python.org/dev/peps/pep-0631/)
* [PEP 633 – Dependency specification in pyproject.toml using an exploded TOML table](https://www.python.org/dev/peps/pep-0633/)
* [PEP 650 – Specifying Installer Requirements for Python Projects](https://www.python.org/dev/peps/pep-0650/)
* [PEP 665 – A file format to list Python dependencies for reproducibility of an application](https://peps.python.org/pep-0665/)

## Projects discussing the use of `pyproject.toml`

Some project are still considering the adoption of the `pyproject.toml` file.
These entries link directly to the project discussion.

* [pyenv](https://github.com/pyenv/pyenv/issues/1233) ⭐ 45,093 | 🐛 55 | 🌐 Shell | 📅 2026-09-08 - Simple Python version management.
* [readthedocs.org](https://github.com/readthedocs/readthedocs.org/issues/7065) ⭐ 8,386 | 🐛 392 | 🌐 Python | 📅 2026-09-10 - Read the Docs hosts documentation for the open source community.
* [AWS SAM](https://github.com/awslabs/aws-sam-cli/issues/1366) ⭐ 6,732 | 🐛 534 | 🌐 Python | 📅 2026-09-10 - CLI tool to build, test, debug, and deploy Serverless applications using AWS SAM.
* [PyOxidizer](https://github.com/indygreg/PyOxidizer/issues/93) ⭐ 6,155 | 🐛 361 | 🌐 Rust | 📅 2024-12-24 - A modern Python application packaging and distribution tool.
* [pycodestyle](https://github.com/PyCQA/pycodestyle/issues/813) ⭐ 5,165 | 🐛 105 | 🌐 Python | 📅 2026-08-16 - A tool to check your Python code against some of the style conventions in PEP 8.
* [Spack](https://github.com/spack/spack/issues/6629) ⭐ 5,121 | 🐛 1,799 | 🌐 Python | 📅 2026-09-10 - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
* [pytype](https://github.com/google/pytype/issues/645) ⚠️ Archived - A static type analyzer for Python code.
* [Invoke](https://github.com/pyinvoke/invoke/issues/537) ⭐ 4,777 | 🐛 461 | 🌐 Python | 📅 2026-04-07 - Library for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
* [Alembic](https://github.com/sqlalchemy/alembic/issues/708) ⭐ 4,387 | 🐛 118 | 🌐 Python | 📅 2026-09-10 - A database migrations tool for SQLAlchemy.
* [flake8](https://github.com/PyCQA/flake8/issues/234) ⭐ 3,822 | 🐛 23 | 🌐 Python | 📅 2026-08-17 - A python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of some python code.
* [prospector](https://github.com/PyCQA/prospector/issues/376) ⭐ 2,085 | 🐛 32 | 🌐 Python | 📅 2026-09-08 - A tool to analyse Python code and output information about errors, potential problems, convention violations and complexity.
* [Radon](https://github.com/rubik/radon/issues/220) ⭐ 2,018 | 🐛 52 | 🌐 Python | 📅 2024-10-20 - A Python tool that computes various metrics from the source code.
* [bumpversion](https://github.com/peritus/bumpversion/issues/192) ⭐ 1,519 | 🐛 93 | 🌐 Python | 📅 2023-07-14 - Version-bump your software with a single command.
  * [bump2version](https://github.com/c4urself/bump2version/issues/42) ⭐ 1,115 | 🐛 115 | 🌐 Python | 📅 2025-02-20 - An interim fork with the intent to merge back to the original project.
* [pytest-benchmark](https://github.com/ionelmc/pytest-benchmark/issues/26) ⭐ 1,450 | 🐛 122 | 🌐 Python | 📅 2026-08-23 - A pytest fixture for benchmarking code.
* [Pylama](https://github.com/klen/pylama/issues/171) ⭐ 1,047 | 🐛 74 | 🌐 Python | 📅 2026-06-22 - Code audit tool for Python and JavaScript. Pylama wraps these tools: pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, Radon, gjslint, eradicate, mypy.
* [gitlint](https://github.com/jorisroovers/gitlint/issues/115) ⭐ 971 | 🐛 63 | 🌐 Python | 📅 2024-07-11 - Linting for your git commit messages.
* [mach-nix](https://github.com/DavHau/mach-nix/issues/14) ⭐ 887 | 🐛 214 | 🌐 Python | 📅 2024-05-20 - Create highly reproducible python environments.
* [nose2](https://github.com/nose-devs/nose2/issues/452) ⭐ 827 | 🐛 45 | 🌐 Python | 📅 2026-09-07 - The successor to nose. Its purpose is to extend unittest to make testing nicer and easier to understand.
* [pypyr](https://github.com/pypyr/pypyr/discussions/232) ⭐ 645 | 🐛 16 | 🌐 Python | 📅 2023-12-19 - Task-runner cli & api for automation pipelines. Automate anything by combining commands, different scripts in different languages & applications into one pipeline process.
* [pyup](https://github.com/pyupio/pyup/issues/332) ⭐ 470 | 🐛 76 | 🌐 Python | 📅 2021-06-24 - tool to update your project's dependencies on GitHub. Runs on pyup.io, comes with a command line interface.
* [zest.releaser](https://github.com/zestsoftware/zest.releaser/issues/295) ⭐ 207 | 🐛 26 | 🌐 Python | 📅 2026-08-11 - Python software releasing made easy and repeatable.
* [Dependency Parser](https://github.com/pyupio/dparse/issues/36) ⭐ 64 | 🐛 20 | 🌐 Python | 📅 2024-11-25 - A parser for Python dependency files.
* [Briefcase Bootstrap Template](https://github.com/beeware/briefcase-template/pull/16) ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2026-09-07 - A template for starting a Python app that will be deployed using briefcase.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-11._
