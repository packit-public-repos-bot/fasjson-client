# Release notes

<!-- towncrier release notes start -->

## v1.1.0

Released on 2024-10-09.

### Changes

- Follow redirects by default (7fc652d)
- Adjust cryptography error message (83e62b5)
- Setup towncrier for release notes generation (#99)
- Fix the readthedocs config (bb83d3a)
- Improve the coverage configuration
- Migrate from toml to tomllib/tomli (cad62f9)
- Improve the Github actions (145c5d8, 0e0bdd7, 1d624af)

### Contributors

Many thanks to the contributors of bug reports, pull requests, and pull request
reviews for this release:

- Aurélien Bompard
- Lenka Segura
- Miro Hrončok
- Ryan Lerch


## v1.0.8

Released on 2023-03-29.

### Changes

- Drop support for Python 3.6 to update dependencies, and add support for Python 3.10 and 3.11
- Update dependencies
- Fix Sphinx config
- Fix CI
- Allow additional operation arguments in `list_all_entities`
- Register the `X-Fields` mask format
- Restore compatibility with `requests` < 2.26.0 to support RHEL9

### Contributors

Many thanks to the contributors of bug reports, pull requests, and pull request
reviews for this release:

- Akashdeep Dhar
- Aurélien Bompard
- Carl George

## v1.0.7

Released on 2022-05-11.

### Development Improvements

- add and configure packit (#268)

### Contributors

Many thanks to the contributors of bug reports, pull requests, and pull request
reviews for this release:

- Stephen Coady
