# Checklist for Python Repositories

- Also see [Checklist for Code](Checklist-Code.md)

## Versioning

- Use PEP440
- Use [Versioneer](https://github.com/python-versioneer/python-versioneer) for obtaining version from Git tag

## Style
- Use [black](https://pypi.org/project/black/) to format the code
- Use [isort](https://pypi.org/project/isort/) to organize imports
- Use [flake8](https://pypi.org/project/flake8/) and [pylint](https://pypi.org/project/pylint/) 
to check code style

## Tests

- For Django projects, follow 2 scoops cookie cutter approach
- For other projects, prefer pytest
    - Put tests into `/tests`

## Commonly Used Libraries

- Use standard library `argparse` for argument parsing
- python-attrs and cattrs for no-boilerplate class creation
- Factory boy for test data creation
