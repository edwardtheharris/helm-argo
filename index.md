---
abstract: >-
   Helm Template documentation master file, created by
   sphinx-quickstart on Sun Apr 28 15:35:08 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
authors:
   - name: Xander Harris
     email: xandertheharris@gmail.com
date: 2024-08-04
title: Template Helm Chart
---

## Repository Contents

````{sidebar}
```{contents}
```
````

```{toctree}
:caption: contents

tests/index.md
```

```{toctree}
:caption: meta

.github/index
license
readme
security
```

## Indices and tables

* {ref}`genindex`
* {ref}`modindex`
* {ref}`search`

```{glossary}
GitHub
   Most likely the site this repository is hosted on. More information is
   available [here](https://github.com).

Helm
   A tool commonly used to deploy applications to {term}`Kubernetes`. More
   information is available [here](https://helm.sh).

Kubernetes
   An ancient Greek word that means 'sailor' or 'navigator', it is the
   most common container orchestration system currently in use. More
   information is available [here](https://kubernetes.io).
```

## Usage

Typical Helm chart rules.

### Chart

```{autoyaml} Chart.yaml
```

### Values

```{autoyaml} values.yaml
```

```{sectionauthor} Xander Harris <xandertheharris@gmail.com>
```
