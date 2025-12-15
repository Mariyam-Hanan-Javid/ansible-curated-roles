# Ansible Curated Roles

[![GitHub Release](https://img.shields.io/github/v/release/rrarireggi-cyber/ansible-curated-roles)](https://github.com/rrarireggi-cyber/ansible-curated-roles/releases/latest)
[![Renovate](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://developer.mend.io/github/rrarireggi-cyber/ansible-curated-roles)
[![GitHub last commit](https://img.shields.io/github/last-commit/rrarireggi-cyber/ansible-curated-roles)](https://github.com/rrarireggi-cyber/ansible-curated-roles/commits/main)
[![License](https://img.shields.io/github/license/rrarireggi-cyber/ansible-curated-roles)](https://github.com/rrarireggi-cyber/ansible-curated-roles/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/rrarireggi-cyber/ansible-curated-roles)](https://github.com/rrarireggi-cyber/ansible-curated-roles/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/rrarireggi-cyber/ansible-curated-roles)](https://github.com/rrarireggi-cyber/ansible-curated-roles/pulls)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Ansible Curated Roles](#ansible-curated-roles)
  - [Usage](#usage)
  - [Release Instructions](#release-instructions)
  - [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

A curated collection of Ansible roles and playbooks maintained by **rrarireggi-cyber**.

These roles are designed for real-world automation use cases and reusable
infrastructure workflows. Contributions and suggestions are welcome.

## Usage

To use this collection, add it as a dependency in your `requirements.yml` file:

```yaml
collections:
  - name: rrarireggi_cyber.general
    # latest version: https://github.com/rrarireggi-cyber/ansible-curated-roles/releases
    version: x.x.x
```

## Release Instructions

```shell
version=vx.x.x
git tag -s $version -m $version
git push origin --tags
```

## License

This project is licensed under the Apache License 2.0 - see the
[LICENSE](LICENSE) file for details.
