---
abstract: Usage guide for a Monero Node.
authors:
    - name: Xander Harris
      email: xandertheharris@gamil.com
date: 2024-08-04
title: Monero Node
---

## Install Node

```{code-block} shell
helm upgrade --install monero oci://tccr.io/truecharts/monero-node -f values.yaml
```

### Values

```{autoyaml} monero/values.yaml
```
