---
title: jx secret wait
linktitle: wait
type: docs
description: 
aliases:
  - jx-secret_wait
---

## jx secret wait

Waits for the mandatory Secrets to be populated from their External Secrets

### Usage

```
jx secret wait
```

### Synopsis

Waits for the mandatory Secrets to be populated from their External Secrets

### Examples

  ```bash
  jx-secret wait

  ```
### Options

```
  -h, --help               help for wait
  -n, --ns string          the namespace to filter the ExternalSecret resources
  -p, --poll duration      the polling period to check if the secrets are valid (default 2s)
  -t, --timeout duration   the maximum amount of time to wait for the secrets to be valid (default 30m0s)
```

### SEE ALSO

* [jx secret](..)	 - External Secrets utility commands

###### Auto generated by spf13/cobra on 25-Feb-2021
