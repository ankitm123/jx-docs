---
title: jx pipeline stop
linktitle: stop
type: docs
description: 
aliases:
  - jx-pipeline_stop
---

## jx pipeline stop

Stops one or more pipelines

***Aliases**: kill*

### Usage

```
jx pipeline stop
```

### Synopsis

Stops the pipeline build.

### Examples

  ```bash
  # Stop a pipeline
  jx pipeline stop foo/bar/master -b 2
  
  # Select the pipeline to stop
  jx pipeline stop

  ```
### Options

```
      --build int       The build number to stop
  -f, --filter string   Filters all the available jobs by those that contain the given text
  -h, --help            help for stop
```

### SEE ALSO

* [jx pipeline](..)	 - commands for working with Jenkins X Pipelines

###### Auto generated by spf13/cobra on 25-Mar-2021
