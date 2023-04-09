============================
Helm chart for mumble server
============================

Char for deploying https://hub.docker.com/r/pvarkiprojekti/mumbleserver in k8s

Development
^^^^^^^^^^^

Uses pre-commit, you need some basic dependencies (run in this directory)::

    pip3 install --user pre-commit detect-secrets
    pre-commit install

As usual using virtualenvs is generally recommended but in this case not strictly mandatory.

Before committing check your work with::

    pre-commit run --all-files ; echo $?

This saves you annoyance of rewriting commit messages when one of the checks fail.
