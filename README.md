# Ansible Execution Environments

This repo contains the definitions for Ansible Execution Environments (EE) that
I use.

## Build Statuses

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/branic/ansible-ee-builds/main.svg)](https://results.pre-commit.ci/latest/github/branic/ansible-ee-builds/main)
![AAP EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/aap-ee-build.yml/badge.svg)
![Ansible EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/ansible-ee-build.yml/badge.svg)
![AWS EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/aws-ee-build.yml/badge.svg)
![Azure EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/azure-ee-build.yml/badge.svg)
![Development EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/development-ee.yml/badge.svg)
![ROSA EE build](https://github.com/branic/ansible-ee-builds/actions/workflows/rosa-ee.yml/badge.svg)

## Contributions

Contributions to this repo are welcomed. New directories must follow the format
that [`ansible-builder`](https://ansible-builder.readthedocs.io/en/latest/) expects.
The name given to the directory should match the name of the EE image.

## Licensing

[GPLv3](./LICENSE)

## Credits

The layout and GitHub automated builds is inspired by
<https://github.com/cloin/ee-builds/>
