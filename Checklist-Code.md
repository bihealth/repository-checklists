# Checklist for Code Repositories

This checklist contains points that should be considered for any code repository.

## .gitignore file

- gitignore.io is a useful resource
- ignore `.*.sw?` for Vim
- ignore `*~` for Emacs and other text editors 
- ignore VSCode files
- ignore JetBrains editor files

## README

- exists either in Markdown or RST (RST only interesting for Python projects)

### Badge Links

- contains link badge to readthedocs
- contains link badge to CI results
- contains link badge to static code analysis (e.g., Codacy)
- contains link badge to coverage information (Codacy and/or(?) Coveralls)
- contains link badge to PyPi if applicable
- contains link badge to Bioconda if applicable

### Sections

- <=3 sentence summary on top
- summary section
  - license information
  - language/platform
  - link to Bioconda if applicable
  - link to any Docker container if applicable
- quickstart section
  - if feasible: installation, run first example
- installation section, or in readthedocs
- options/configuration section, or in readthedocs

## Continuous Integration

- should exist
- currently, Github Actions are preferred

## Large File Storage

- use for any (binary) file above a few kb
- can be ignored if in total below 50MB of files that are expected to "never" change

## Meta Files

- code of conduct, pypa one is reasonable
- contributing file, describe branches and pull request targets
- GitHub issue templates for bugs and issues, standard ones are a good starting point
