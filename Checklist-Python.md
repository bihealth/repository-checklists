# Checklist for Python Repositories

- Also see [Checklist for Code](Checklist-Code.md)

## Versioning

- Use PEP440
- Use [Versioneer](https://github.com/python-versioneer/python-versioneer) for obtaining version from Git tag

## Tests

- For Django projects, follow 2 scoops cookie cutter approach
- For other projects, prefer pytest
    - Put tests into `/tests`

## Commonly Used Libraries

- Use standard library `argparse` for argument parsing
- python-attrs and cattrs for no-boilerplate class creation
- Factory boy for test data creation

## Includes

- Group includes as system, external, this project
- isort profile see snappy
- absolute imports

## Linting and Static Checks

- Codacy with local prospector setup
- Black line length 100
