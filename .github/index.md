---
abstract: Continuous Integration, Delivery, and Deployment.
authors:
    - name: Xander Harris
      email: xandertheharris@gamil.com
date: 2024-08-04
title: CI/CD usage guide
---

Or something like it.

## GitHub Action Workflows

The following workflows are in use by this repository.

### Documentation Workflow

[![Documentation](https://github.com/edwardtheharris/helm-template/actions/workflows/documentation.yml/badge.svg)](https://github.com/edwardtheharris/helm-template/actions/workflows/documentation.yml)

```{autoyaml} .github/workflows/documentation.yml
```

### Helm Workflow

[![Test Helm Chart](https://github.com/edwardtheharris/helm-template/actions/workflows/helm.yml/badge.svg)](https://github.com/edwardtheharris/helm-template/actions/workflows/helm.yml)

```{autoyaml} .github/workflows/helm.yml
```

## Dependabot Settings

[![Dependabot Updates](https://github.com/edwardtheharris/helm-template/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/edwardtheharris/helm-template/actions/workflows/dependabot/dependabot-updates)

```{autoyaml} .github/dependabot.yml
```
