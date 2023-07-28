# cachito-pip-without-metadata

Repository for testing projects that do not contain any setup files (setup.py, setup.cfg, pyproject.toml).

In such cases, the project name will be resolved from the repository origin url.
If the package is at a subpath, the normalized subpath will be appended to the resolved project name
(project version will be omited).
